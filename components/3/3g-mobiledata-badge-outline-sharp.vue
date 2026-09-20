<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_kzvabdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:3g-mobiledata-badge-outline-sharp" /></template>
<style>
.q_kzvabdl {
  fill: currentColor;
  d: path("M2 20V4h20v16zm1-1h18V5H3zm0 0V5zm9.5-2.5h6v-5H16v1h1.5v3h-4v-7h5v-1h-6zm-7 0h5v-4L10 12l.5-.5v-4h-5v1h4v3h-4v1h4v3h-4z");
}

</style>
