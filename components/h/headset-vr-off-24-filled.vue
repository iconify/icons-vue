<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzaq4mmhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headset-vr-off-24-filled" /></template>
<style>
.yzaq4mmhn {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-1.48-1.48c-.39.129-.807.2-1.24.2h-1.546a4 4 0 0 1-2.163-.636l-2.156-1.386a.25.25 0 0 0-.27 0L9.71 19.865a4 4 0 0 1-2.163.636H6a4 4 0 0 1-4-4V14h-.25a.75.75 0 0 1-.75-.75v-3.5A.75.75 0 0 1 1.75 9H2c0-1.606.948-2.989 2.314-3.625L2.22 3.28a.75.75 0 0 1 0-1.06M14.25 3a.75.75 0 0 1 .75.75V5h3a4 4 0 0 1 4 4h.25a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-.75.75H22v2.5a4 4 0 0 1-.459 1.86L16.181 13h1.069a.75.75 0 0 0 0-1.5h-2.5l-.065.003L8.182 5H9V3.75A.75.75 0 0 1 9.75 3zm-7.5 8.5a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5z");
}

</style>
