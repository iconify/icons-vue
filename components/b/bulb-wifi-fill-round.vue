<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk60bvb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-wifi-fill-round" /></template>
<style>
.gk60bvb_f {
  fill: currentColor;
  d: path("M20.01 7.025A12.9 12.9 0 0 1 21 12a1 1 0 0 1-2 0a11 11 0 0 0-3.222-7.778a1 1 0 0 1 1.414-1.414a12.9 12.9 0 0 1 2.818 4.217m-3.695 1.531A8.9 8.9 0 0 1 17 12a1 1 0 0 1-2 0a6.9 6.9 0 0 0-.533-2.679A6.9 6.9 0 0 0 12.95 7.05a.997.997 0 0 1 0-1.414a1 1 0 0 1 1.414 0a8.9 8.9 0 0 1 1.951 2.92M11 16.021V17a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-.979c-.022-.075-.064-.144-.103-.211c-.147-.246-.328-.474-.502-.702C3.696 14.191 3 13.209 3 12a5 5 0 0 1 10 0c0 1.209-.696 2.191-1.395 3.108c-.174.228-.355.456-.502.702c-.039.067-.081.136-.103.211M10 22H6a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2");
}

</style>
