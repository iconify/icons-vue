<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy-gs39nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:adb-outline" /></template>
<style>
.yy-gs39nb {
  fill: currentColor;
  d: path("M6.077 11.192v-.846q0-1.53.688-2.778t1.85-2.062L7.03 3.919l.74-.765l1.798 1.798q.535-.261 1.167-.395T12 4.423t1.266.134t1.167.395l1.798-1.798l.74.765l-1.586 1.587q1.163.815 1.85 2.062q.688 1.248.688 2.778v.846zm9.068-1.931q.24-.24.24-.607t-.24-.607t-.606-.24t-.607.24t-.24.607t.24.607t.607.239t.606-.24m-5.077 0q.24-.239.24-.606t-.24-.607t-.607-.24t-.606.24t-.24.607t.24.607t.606.239t.607-.24M7.797 19.627q-1.72-1.72-1.72-4.203V12.04h11.846v3.384q0 2.483-1.72 4.203T12 21.346t-4.203-1.72");
}

</style>
