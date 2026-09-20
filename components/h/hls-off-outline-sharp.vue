<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf_brbc5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hls-off-outline-sharp" /></template>
<style>
.kf_brbc5t {
  fill: currentColor;
  d: path("m17.517 14.692l-1.634-1.634V13h.81v.712l.095.096h2.52v-1.5h-3.5v-3h4.384V11h-.884v-.808h-2.616v1.5h3.5v3zm-14.21 0V9.308h.885v2h2.616v-2h.884v5.384h-.884v-2.5H4.192v2.5zm16.526 6.562L2.746 4.167l.708-.713L20.54 20.546zm-9.602-6.562v-3.748l.885.885v1.979H13.1l.885.884z");
}

</style>
