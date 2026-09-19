<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cozu51o2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-offline-bolt" /></template>
<style>
.cozu51o2b {
  fill: currentColor;
  d: path("M12 2.02c-5.51 0-9.98 4.47-9.98 9.98s4.47 9.98 9.98 9.98s9.98-4.47 9.98-9.98S17.51 2.02 12 2.02M11.48 20v-6.26H8L13 4v6.26h3.35z");
}

</style>
