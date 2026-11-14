<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="pm27n5b9s"/><path class="q-q0h9b1f"/></g><path class="zdgqqoi4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flag-off-bold-duotone" /></template>
<style>
.pm27n5b9s {
  d: path("M14.5049 14.5049C13.7854 14.4119 13.076 14.2306 12.3945 13.958C10.8318 13.333 9.12109 13.1758 7.4707 13.5059L5.75 13.8496V21.25C5.75 21.6642 5.41421 22 5 22C4.58579 22 4.25 21.6642 4.25 21.25V4.24999L14.5049 14.5049Z");
}

.q-q0h9b1f {
  d: path("M7.4707 3.50585C9.12109 3.17578 10.8318 3.33301 12.3945 3.958L12.5986 4.03905C14.1596 4.66339 15.8777 4.7807 17.5088 4.37304C18.2661 4.18374 19 4.7566 19 5.5371V12.9033C19 13.5475 18.5615 14.1094 17.9365 14.2656L17.7646 14.3086L7.0459 3.58984L7.4707 3.50585Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zdgqqoi4b {
  fill: currentColor;
  d: path("M1.46967 1.46967C1.76256 1.17678 2.23732 1.17678 2.53022 1.46967L22.5302 21.4697C22.8231 21.7626 22.8231 22.2373 22.5302 22.5302C22.2373 22.8231 21.7626 22.8231 21.4697 22.5302L1.46967 2.53022C1.17678 2.23732 1.17678 1.76256 1.46967 1.46967Z");
}

</style>
