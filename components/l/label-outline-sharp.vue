<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dopk0kiyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-outline-sharp" /></template>
<style>
.dopk0kiyj {
  fill: currentColor;
  d: path("M3 19V5h12.635L21 12l-5.365 7zm1-1h11.135l4.615-6l-4.615-6H4zm7.885-6");
}

</style>
