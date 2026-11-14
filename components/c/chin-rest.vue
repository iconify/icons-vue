<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc1pl8bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chin-rest" /></template>
<style>
.rc1pl8bry {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 5.268V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.768q-5 .252-5 3.982q0 1.16 1.189 2.498q.811.912.811 1.502q0 .224-.975.884Q4.75 15.845 4.75 18q0 4.25 7.25 4.25T19.25 18q0-2.155-2.525-3.866q-.975-.66-.975-.884q0-.59.811-1.502Q17.75 10.41 17.75 9.25q0-3.73-5-3.982M8 17.75q0-2.25 4-2.25q1.511 0 2.612.508Q16 16.649 16 17.75Q16 20 12 20t-4-2.25");
}

</style>
