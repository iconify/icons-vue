<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4kt96b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:4g-plus-mobiledata-sharp" /></template>
<style>
.g4kt96b9z {
  fill: currentColor;
  d: path("M20.192 14.5v-2h-2v-1h2v-2h1v2h2v1h-2v2zm-14.384 2v-3h-4v-6h1v5h3v-5h1v5h1v1h-1v3zm3.769 0v-9h7v1h-6v7h5v-3h-2v-1h3v5z");
}

</style>
