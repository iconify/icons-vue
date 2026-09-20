<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fosh3p38i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ambulance-sharp" /></template>
<style>
.fosh3p38i {
  fill: currentColor;
  d: path("M11.5 4.846v-3h1v3zM7.921 6.06L5.633 3.77l.713-.713l2.288 2.288zM6.577 17.423H10v-1.461H6.577zm7.423 0h3.423v-1.461H14zM16.602 11l3.148-3.142l-.627-.627l-2.521 2.51l-1.11-1.11l-.627.633zm-2.13.816q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164q1.165 1.165 1.165 2.836t-1.165 2.835t-2.835 1.165t-2.836-1.165M4 22v-7.846L6.162 8h3.761V6.462h1.564q-.274.58-.419 1.208t-.145 1.31V9H6.889l-1.61 4.385h7.438q.904.944 2.087 1.462q1.183.519 2.504.519q.704 0 1.383-.154q.68-.153 1.309-.445V22h-1.23v-2H5.23v2z");
}

</style>
