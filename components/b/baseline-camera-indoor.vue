<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibxignj9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-camera-indoor" /></template>
<style>
.ibxignj9d {
  fill: currentColor;
  d: path("M12 3L4 9v12h16V9zm4 13.06L14 15v1c0 .55-.45 1-1 1H9c-.55 0-1-.45-1-1v-4c0-.55.45-1 1-1h4c.55 0 1 .45 1 1v1l2-1.06z");
}

</style>
