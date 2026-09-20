<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlf759bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:install-mobile-outline-sharp" /></template>
<style>
.tlf759bvs {
  fill: currentColor;
  d: path("M5 23V1h9v2H7v1h7v2H7v12h10v-2h2v7zm2-3v1h10v-1zm11-6l-5-5l1.4-1.4l2.6 2.6V3h2v7.2l2.6-2.6L23 9zM7 4V3zm0 16v1z");
}

</style>
