<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_16w0bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:aspect-ratio-fill" /></template>
<style>
.l_16w0bjf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 7C1 4.7909 2.7909 3 5 3L19 3C21.2091 3 23 4.7909 23 7L23 17C23 19.2091 21.2091 21 19 21L5 21C2.7909 21 1 19.2091 1 17L1 7ZM14 7C13.4477 7 13 7.4477 13 8C13 8.5523 13.4477 9 14 9L17 9L17 12C17 12.5523 17.4477 13 18 13C18.5523 13 19 12.5523 19 12L19 9C19 7.8954 18.1046 7 17 7L14 7ZM7 12C7 11.4477 6.5523 11 6 11C5.4477 11 5 11.4477 5 12L5 15C5 16.1046 5.8954 17 7 17L10 17C10.5523 17 11 16.5523 11 16C11 15.4477 10.5523 15 10 15L7 15L7 12Z");
}

</style>
