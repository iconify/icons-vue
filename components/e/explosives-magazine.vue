<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi509b1st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:explosives-magazine" /></template>
<style>
.yi509b1st {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.001 4.816q2.28.37 2.48 2.819q.755-.385 1.894-.385h.25Q21 7.25 21 10.625v8.25q0 3.375-3.375 3.375h-.25q-1.784 0-2.625-.943q-.841.943-2.625.943h-.25q-1.784 0-2.625-.943q-.841.943-2.625.943h-.25Q3 22.25 3 18.875v-8.25Q3 7.25 6.375 7.25h.25q1.139 0 1.894.385q.215-2.633 2.833-2.863q.273-.927 1.27-1.629q.721-.507.957-.978q.067-.134.18-.232q.112-.097.254-.145q.141-.047.29-.036q.149.01.282.077q.066.033.125.079q.058.045.107.101q.048.055.085.12q.036.064.06.134q.023.07.032.143t.004.147t-.025.145t-.052.137q-.405.81-1.436 1.535q-.305.215-.484.446");
}

</style>
