<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smus4_b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-a-photo-sharp" /></template>
<style>
.smus4_b8m {
  fill: currentColor;
  d: path("M19 7V5h-2V4h2V2h1v2h2v1h-2v2zm-8 9.73q1.567 0 2.649-1.081T14.731 13t-1.082-2.649T11 9.269t-2.649 1.082T7.269 13t1.082 2.649T11 16.731m0-1q-1.165 0-1.948-.783T8.269 13t.783-1.948T11 10.269t1.948.783t.783 1.948t-.783 1.948t-1.948.783M2 20V6h4.573l1.85-2h6.193v3.385h2v2H20V20z");
}

</style>
