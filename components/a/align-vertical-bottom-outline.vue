<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2-u9hb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-vertical-bottom-outline" /></template>
<style>
.v2-u9hb8i {
  fill: currentColor;
  d: path("M2 22v-2h20v2zm5-4V2h3v16zm7 0V8h3v10z");
}

</style>
