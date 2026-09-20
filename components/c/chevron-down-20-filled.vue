<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s0o9is0ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-down-20-filled" /></template>
<style>
.s0o9is0ie {
  fill: currentColor;
  d: path("M15.794 7.733a.75.75 0 0 1-.026 1.06l-5.25 5.001a.75.75 0 0 1-1.035 0l-5.25-5a.75.75 0 0 1 1.034-1.087l4.734 4.509l4.733-4.51a.75.75 0 0 1 1.06.027");
}

</style>
