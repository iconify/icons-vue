<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hk7-qtbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-imba" /></template>
<style>
.hk7-qtbof {
  fill: var(--svg-color--16cec6, #16cec6);
  d: path("M29.762 13.264C26.689 7.366-.746 1.341 2.224 5.239s16.13 9.245 16.909 9.345c-4.036 1.29-14.813 3.6-12.5 5.552s13.262-.227 13.244-.193c-3.034 2.327-6.811 9.349-3.016 7.849c5.983-2.368 14.692-11.092 12.901-14.528");
}

</style>
