<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1cg2rb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:interference-pattern" /></template>
<style>
.q1cg2rb6z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.875 6.75q-1.836 0-3.103 5.068q-.044.177-.002.355l.002.009q1.267 5.068 3.103 5.068q1.339 0 2.375-2.696q1.036 2.696 2.375 2.696T12 14.554q1.036 2.696 2.375 2.696t2.375-2.696q1.036 2.696 2.375 2.696q1.835 0 3.102-5.067l.001-.001q.041-.164.007-.329l-.007-.035Q20.961 6.75 19.125 6.75q-1.339 0-2.375 2.696q-1.036-2.696-2.375-2.696T12 9.446Q10.964 6.75 9.625 6.75T7.25 9.446Q6.214 6.75 4.875 6.75m0 9q-.649 0-1.602-3.75q.953-3.75 1.602-3.75T6.477 12q-.953 3.75-1.602 3.75m4.75 0q-.649 0-1.602-3.75q.953-3.75 1.602-3.75T11.227 12q-.953 3.75-1.602 3.75m4.75 0q-.649 0-1.602-3.75q.953-3.75 1.602-3.75T15.977 12q-.953 3.75-1.602 3.75m4.75 0q-.649 0-1.602-3.75q.953-3.75 1.602-3.75T20.727 12q-.953 3.75-1.602 3.75");
}

</style>
