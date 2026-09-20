<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3pvvrbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-forward-ios-rounded" /></template>
<style>
.f3pvvrbqw {
  fill: currentColor;
  d: path("M15.187 12L7.47 4.285q-.221-.221-.218-.532q.003-.31.224-.532Q7.698 3 8.009 3q.31 0 .532.221l7.636 7.643q.242.242.354.54t.111.596t-.111.596t-.354.54L8.535 20.78q-.222.221-.53.218q-.307-.003-.528-.224t-.221-.532t.221-.531z");
}

</style>
