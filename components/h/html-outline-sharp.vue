<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwub-zbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:html-outline-sharp" /></template>
<style>
.mwub-zbjw {
  fill: currentColor;
  d: path("M0 15V9h1.5v2h2V9H5v6H3.5v-2.5h-2V15zm7.75 0v-4.5H6V9h5v1.5H9.25V15zM12 15V9h6.5v6H17v-4.5h-1V14h-1.5v-3.5h-1V15zm8 0V9h1.5v4.5H24V15z");
}

</style>
