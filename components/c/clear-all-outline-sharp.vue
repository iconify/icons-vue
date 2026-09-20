<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnre-0bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clear-all-outline-sharp" /></template>
<style>
.xnre-0bwl {
  fill: currentColor;
  d: path("M4 15.885v-1h12.25v1zM5.866 12.5v-1h12.25v1zM7.75 9.116v-1H20v1z");
}

</style>
