<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2_7hdbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:h-mobiledata-outline-rounded" /></template>
<style>
.q2_7hdbuo {
  fill: currentColor;
  d: path("M8.5 12.5v4q0 .213-.144.356T7.999 17t-.356-.144T7.5 16.5v-9q0-.213.144-.356T8.001 7t.356.144t.143.356v4h7v-4q0-.213.144-.356T16.001 7t.356.144t.143.356v9q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356v-4z");
}

</style>
