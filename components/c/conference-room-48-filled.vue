<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zwql7gblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:conference-room-48-filled" /></template>
<style>
.zwql7gblo {
  fill: currentColor;
  d: path("m22.503 7.776l14.5 3c.58.12.997.632.997 1.224v24a1.25 1.25 0 0 1-.997 1.224l-14.5 3A1.25 1.25 0 0 1 21 39.002V9a1.25 1.25 0 0 1 1.503-1.225M18 10l.128 27.994l-.128.007h-6.75a1.25 1.25 0 0 1-1.243-1.123L10 36.751v-25.5c0-.648.492-1.18 1.122-1.244L11.25 10zm8.5 12.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
