<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4mzwey4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fan-mail" /></template>
<style>
.b4mzwey4q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 3.75H6q-1.76 0-3.005 1.245q-.361.361-.617.765q.067-.011.136-.01q.149.003.286.062q.136.06.24.167l5.241 5.436q.192-.513.61-1.007Q10.18 8.884 12 9.455q1.82-.571 3.109.953q.418.494.61 1.007l5.241-5.436q.104-.107.24-.167q.137-.059.286-.062q.069-.001.136.01q-.256-.404-.617-.765Q19.76 3.75 18 3.75m-2.704 10.264l-2.743 2.993q-.05.054-.11.098q-.059.044-.126.075t-.139.049q-.072.017-.145.02q-.074.004-.147-.008q-.073-.011-.143-.036q-.069-.026-.132-.064t-.118-.088q-.024-.022-.046-.046l-2.743-2.993L1.96 7.021q-.045-.047-.081-.101Q1.75 7.434 1.75 8v8q0 1.76 1.245 3.005T6 20.25h12q1.76 0 3.005-1.245T22.25 16V8q0-.566-.129-1.08q-.036.054-.081.101z");
}

</style>
