<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5viabbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ambulance-outline-sharp" /></template>
<style>
.f5viabbew {
  fill: currentColor;
  d: path("M11.5 4.846v-3h1v3zM7.921 6.06L5.633 3.77l.713-.713l2.288 2.288zM4 22v-7.846L6.162 8h3.761V6.462h1.564q-.274.58-.419 1.208t-.145 1.31V9H6.889l-1.61 4.385h7.438q.252.292.547.545q.294.253.636.454H5V19h14v-3.883q.275-.055.516-.148q.24-.092.484-.202V22h-1.23v-2H5.23v2zm2.577-4.577H10v-1.461H6.577zm7.423 0h3.423v-1.461H14zM5 19v-4.615zm11.602-8l3.148-3.142l-.627-.627l-2.521 2.51l-1.11-1.11l-.627.633zm-2.13.816q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164q1.165 1.165 1.165 2.836t-1.165 2.835t-2.835 1.165t-2.836-1.165");
}

</style>
