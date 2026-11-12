<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cudmambxa"/><path class="j45ubn33o"/><path class="t53txddyt"/><path class="d91dvubal"/><path class="dlm0nfcry"/><path class="pq5xj2bli"/><path class="zfge7hb-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-minimalistic-broken" /></template>
<style>
.cudmambxa {
  d: path("M5 8C5 6.11438 5 5.17157 5.58579 4.58579C6.17157 4 7.11438 4 9 4H15C16.8856 4 17.8284 4 18.4142 4.58579C19 5.17157 19 6.11438 19 8V15.8831C19 16.6438 18.6809 17.3697 18.1203 17.8841C14.6584 21.0607 9.3416 21.0607 5.87966 17.8841C5.31911 17.3697 5 16.6438 5 15.8831V12");
}

.d91dvubal {
  d: path("M14 11.9167C14 13.0672 13.1046 14 12 14C10.8954 14 10 13.0672 10 11.9167C10 11.1967 10.783 10.2359 11.3691 9.61743C11.7161 9.2513 12.2839 9.2513 12.6309 9.61743C13.217 10.2359 14 11.1967 14 11.9167Z");
}

.dlm0nfcry {
  d: path("M19 11H17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j45ubn33o {
  d: path("M19 8L17 8");
}

.pq5xj2bli {
  d: path("M12 21V22");
}

.t53txddyt {
  d: path("M19 14H17");
}

.zfge7hb-h {
  d: path("M14 4C14 2.89543 13.1046 2 12 2C10.8954 2 10 2.89543 10 4");
}

</style>
