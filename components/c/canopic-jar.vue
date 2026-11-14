<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwcba5bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:canopic-jar" /></template>
<style>
.fwcba5bqh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 3.774V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v1.274q-4.78.316-4.99 4.803q-2.635 1.776-2.635 6.048q0 4.47 2.887 6.944q.102.088.228.134t.26.047h10q.134 0 .26-.047q.126-.046.228-.134q2.887-2.474 2.887-6.944q0-4.272-2.635-6.048q-.21-4.487-4.99-4.803M12 5.25q3.801 0 4.203 3H7.797q.402-3 4.203-3");
}

</style>
