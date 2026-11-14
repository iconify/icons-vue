<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy8g0abid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:house-thermometer" /></template>
<style>
.zy8g0abid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v5.656q-.116-.159-.25-.306V15q0-3-3-3t-3 3v2.061q-.733.804-.939 1.976q-.21 1.193.221 2.213H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568m11.357 10.112q.182-1.033.958-1.65V15q0-1.75 1.75-1.75T19.75 15v2.605q.776.617.958 1.65q.223 1.262-.601 2.245q-.825.982-2.107.982t-2.107-.982q-.824-.983-.601-2.245M17.75 18q0 .099-.026.194t-.074.181q-.05.086-.12.155q-.069.07-.155.12q-.505.291-.606.865t.273 1.021t.958.446q.583 0 .958-.446q.374-.447.273-1.021t-.606-.865q-.086-.05-.155-.12q-.07-.069-.12-.155t-.074-.181q-.026-.095-.026-.194v-3q0-.25-.25-.25t-.25.25z");
}

</style>
