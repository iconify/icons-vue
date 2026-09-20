<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":416};
const content = `<path class="e0l8_jbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:elevenlabs-icon" /></template>
<style>
.e0l8_jbqo {
  d: path("M170.667 0H256v415.289h-85.333zM0 0h85.333v415.289H0z");
}

</style>
