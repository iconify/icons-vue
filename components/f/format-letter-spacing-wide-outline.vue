<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9nq6hzxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-letter-spacing-wide-outline" /></template>
<style>
.x9nq6hzxc {
  fill: currentColor;
  d: path("M3 20V4h2v16zm16 0V4h2v16zM7.35 17L11.1 7h1.8l3.75 10H14.9l-.85-2.55H10L9.1 17zm3.15-4h3l-1.45-4.15z");
}

</style>
