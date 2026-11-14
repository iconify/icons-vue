<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut30yzado"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:falling-rocks-sign" /></template>
<style>
.ut30yzado {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.972 15.728l-5.026-8.993Q13.979 5.007 12 5.007T9.054 6.735l-3.358 6.01q.021-.024.044-.045q.055-.051.118-.089q.063-.039.132-.064t.142-.038q.073-.011.147-.008t.145.02t.139.048t.127.074t.11.097l6.25 6.75q.102.11.153.25t.046.289t-.068.284q-.062.136-.171.237q-.055.051-.118.089q-.063.039-.132.064t-.142.038q-.073.011-.147.008t-.145-.02t-.139-.048t-.127-.074t-.11-.097L5.7 13.76q-.066-.072-.112-.157q-.045-.085-.068-.18q-.022-.094-.02-.191q.003-.097.029-.19l-1.501 2.686q-.943 1.687.035 3.355t2.911 1.667h10.052q1.933 0 2.911-1.667t.035-3.355M12 9.25q1.75 0 1.75 1.75T12 12.75T10.25 11T12 9.25m0 6.5q0-2.25 2.25-2.25t2.25 2.25T14.25 18T12 15.75");
}

</style>
