<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="y1dlddbuh"/><path class="n-edxrb5m"/><path class="etnrzve5d"/><path class="fpwgf-01r"/><path class="mq8h73bry"/><path class="a2zk7ej_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:capacitorjs-icon" /></template>
<style>
.a2zk7ej_b {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m115.359 100.985l39.659-39.601l-15.271-15.186z");
}

.etnrzve5d {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m140.517 154.896l-39.658 39.601l15.267 15.182z");
}

.fpwgf-01r {
  fill: var(--svg-color--53b9ff, #53b9ff);
  d: path("M194.57 100.985L256 39.478L216.431 0l-61.412 61.384L93.917.311L54.365 39.913L216.01 201.761l39.552-39.602z");
}

.mq8h73bry {
  fill: var(--svg-color--119eff, #119eff);
  d: path("m115.36 100.987l39.659-39.602L93.917.313L54.365 39.914z");
}

.n-edxrb5m {
  fill: var(--svg-color--119eff, #119eff);
  d: path("m140.517 154.896l-39.658 39.601l61.097 61.069l39.552-39.602z");
}

.y1dlddbuh {
  fill: var(--svg-color--53b9ff, #53b9ff);
  d: path("M39.863 54.115L.311 93.716l60.995 61.179L0 216.385l39.428 39.619l61.43-61.507l61.097 61.068l39.552-39.602z");
}

</style>
