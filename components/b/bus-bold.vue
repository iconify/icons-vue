<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lfq9t79ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bus-bold" /></template>
<style>
.lfq9t79ds {
  fill: currentColor;
  d: path("M184 28H72a36 36 0 0 0-36 36v144a20 20 0 0 0 20 20h28a20 20 0 0 0 20-20v-16h48v16a20 20 0 0 0 20 20h28a20 20 0 0 0 20-20V64a36 36 0 0 0-36-36M60 168v-56h136v56ZM72 52h112a12 12 0 0 1 12 12v24H60V64a12 12 0 0 1 12-12m8 152H60v-12h20Zm96 0v-12h20v12Zm-68-64a16 16 0 1 1-16-16a16 16 0 0 1 16 16m72 0a16 16 0 1 1-16-16a16 16 0 0 1 16 16m76-60v24a12 12 0 0 1-24 0V80a12 12 0 0 1 24 0M24 80v24a12 12 0 0 1-24 0V80a12 12 0 0 1 24 0");
}

</style>
