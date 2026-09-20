<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr7rs06ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:eda-sharp" /></template>
<style>
.wr7rs06ls {
  fill: currentColor;
  d: path("M3 23v-7h5.45l3.4 4.525l6.175-6.175l2.35-1.425l2.65 1.975l-8.1 8.1zm4-11V2h2v10h2V1h2v11h2V3h2v9.575l-4.95 4.9L9.45 14H3V4h2v8z");
}

</style>
