<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjn26p5om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrowhead-stone" /></template>
<style>
.vjn26p5om {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.871 9.98l1.172-3.127q.509-1.356-.516-2.38q-1.024-1.025-2.38-.516l-3.128 1.172q-.958.36-.982 1.383q-.023 1.023.917 1.427l.732.314L2.97 19.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163L15.747 9.314l.314.732q.404.94 1.427.917q1.023-.024 1.383-.983");
}

</style>
