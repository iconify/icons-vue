<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#SVGSQhNybkz)" transform="translate(-.594 2.515)scale(.13111)" class="obg7u3o0l"><path class="e5ta_gb9t"/><path class="sh1fbfcly"/></g><defs><filter id="SVGSQhNybkz" width="213.57" height="178.91" x="19.784" y="13.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="3.043"/><feGaussianBlur stdDeviation="7.608"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.3 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_8_35"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_8_35" result="shape"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-warp" /></template>
<style>
.e5ta_gb9t {
  d: path("M127.72 25.57h68.386c11.07 0 20.044 9.273 20.044 20.712v80.413c0 11.439-8.974 20.712-20.044 20.712H98.244z");
}

.ft5dv1b6b {
  fill: none;
}

.obg7u3o0l {
  fill: var(--svg-color--121212, #121212);
}

.sh1fbfcly {
  d: path("M109.96 48.652H54.87c-10.976 0-19.873 9.273-19.873 20.712v80.413c0 11.439 8.898 20.712 19.873 20.712h67.803l2.719-11.335H83.453z");
}

</style>
