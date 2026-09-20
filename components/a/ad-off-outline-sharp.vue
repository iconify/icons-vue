<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-bog4ldb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ad-off-outline-sharp" /></template>
<style>
.w-bog4ldb {
  fill: currentColor;
  d: path("m19.775 22.6l-1.6-1.6H3V5.825L1.4 4.2l1.4-1.4l18.4 18.4zM5 19h11.175L5 7.825zm16-.825l-2-2V8h-8.175l-5-5H21z");
}

</style>
