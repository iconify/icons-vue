<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vynzm1buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headset-vr-off-24-regular" /></template>
<style>
.vynzm1buf {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-1.48-1.48c-.39.129-.807.2-1.24.2h-1.546a4 4 0 0 1-2.163-.636l-2.156-1.386a.25.25 0 0 0-.27 0L9.71 19.865a4 4 0 0 1-2.163.636H6a4 4 0 0 1-4-4V14h-.25a.75.75 0 0 1-.75-.75v-3.5A.75.75 0 0 1 1.75 9H2c0-1.606.948-2.989 2.314-3.625L2.22 3.28a.75.75 0 0 1 0-1.06m3.27 4.332A2.5 2.5 0 0 0 3.5 9v7.5A2.5 2.5 0 0 0 6 19h1.546c.48 0 .948-.138 1.351-.397l2.157-1.386a1.75 1.75 0 0 1 1.892 0l2.156 1.386c.404.259.873.397 1.352.397h1.485zM14.25 3a.75.75 0 0 1 .75.75V5h3a4 4 0 0 1 4 4h.25a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-.75.75H22v2.5a4 4 0 0 1-.459 1.86l-1.146-1.147c.067-.226.105-.465.105-.713V9A2.5 2.5 0 0 0 18 6.5H9.682L8.182 5H9V3.75A.75.75 0 0 1 9.75 3zm-5 8.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1 0-1.5zm8 0a.75.75 0 0 1 0 1.5h-1.068l-1.497-1.497l.065-.003z");
}

</style>
