<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-jhjud8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fort-sharp" /></template>
<style>
.b-jhjud8w {
  fill: currentColor;
  d: path("M1 21v-4l2-2V9L1 7V3h2v2h2V3h2v2h2V3h2v4L9 9v1h6V9l-2-2V3h2v2h2V3h2v2h2V3h2v4l-2 2v6l2 2v4h-9v-5h-4v5z");
}

</style>
