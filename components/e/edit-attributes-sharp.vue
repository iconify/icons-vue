<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv9pr6b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-attributes-sharp" /></template>
<style>
.dv9pr6b7w {
  fill: currentColor;
  d: path("M7 16q-1.671 0-2.835-1.164Q3 13.67 3 12t1.165-2.835T7 8h10q1.671 0 2.836 1.165Q21 10.329 21 12t-1.164 2.836T17 16zm1.05-2.161l3.089-3.089l-.627-.627l-2.462 2.462l-.961-.962l-.628.627z");
}

</style>
