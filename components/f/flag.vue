<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvedy3bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:flag" /></template>
<style>
.gvedy3bot {
  fill: currentColor;
  d: path("M14.4 6L14 4H5v17h2v-7h5.6l.4 2h7V6z");
}

</style>
