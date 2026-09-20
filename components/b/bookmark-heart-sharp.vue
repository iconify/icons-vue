<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpdlfiqat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-heart-sharp" /></template>
<style>
.gpdlfiqat {
  fill: currentColor;
  d: path("M12 13.742q1.102-1.001 1.755-1.649q.653-.647 1.02-1.1t.489-.806q.12-.351.12-.755q0-.766-.547-1.32q-.548-.554-1.306-.554q-.447 0-.861.182q-.415.182-.67.502q-.258-.32-.668-.502q-.409-.182-.87-.182q-.756 0-1.301.552t-.545 1.316q0 .403.108.745q.109.343.476.796q.367.454 1.027 1.111T12 13.742M6 19.5V4h12v15.5l-6-2.583z");
}

</style>
