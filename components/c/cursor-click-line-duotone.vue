<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rco-36b_a"/><path class="e9g5-7bqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cursor-click-line-duotone" /></template>
<style>
.e9g5-7bqw {
  d: path("M15.8009 17.7438L18.7153 20.6581L18.7157 20.6585L18.7161 20.6589C19.0172 20.9601 19.1678 21.1108 19.3362 21.1805C19.5606 21.2734 19.8128 21.2734 20.0372 21.1805C20.2055 21.1108 20.3564 20.9599 20.6581 20.6581C20.9599 20.3564 21.1108 20.2055 21.1805 20.0372C21.2734 19.8128 21.2734 19.5606 21.1805 19.3362C21.1108 19.1679 20.96 19.0171 20.6585 18.7157L20.6581 18.7153L17.7438 15.8009L18.6338 14.9109C19.5449 13.9998 20.0004 13.5443 19.8929 13.0546C19.7853 12.565 19.1808 12.3423 17.972 11.8969L17.9719 11.8969L17.9717 11.8968L13.9394 10.4112C11.5274 9.52256 10.3214 9.07826 9.69976 9.69976C9.07826 10.3214 9.52256 11.5274 10.4112 13.9394L11.8968 17.9717V17.9719L11.8968 17.972C12.3423 19.1809 12.565 19.7853 13.0546 19.8929C13.5443 20.0004 13.9998 19.5449 14.9109 18.6338L15.8009 17.7438Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rco-36b_a {
  d: path("M10.25 2.75V5.25M2.75 10.25H5.25M4.5 4.5L6.25 6.25M15.4504 4.65002L14.1504 5.95002M4.65039 15.45L5.95039 14.15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
