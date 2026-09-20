<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf4rqy1xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-arrow-up-outline-sharp" /></template>
<style>
.wf4rqy1xp {
  fill: currentColor;
  d: path("m12 10.8l-4.6 4.6L6 14l6-6l6 6l-1.4 1.4z");
}

</style>
