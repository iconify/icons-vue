<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trykcjbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fitbit-arrow-downward-sharp" /></template>
<style>
.trykcjbgu {
  fill: currentColor;
  d: path("m12 18l-6-6l1.4-1.4l3.6 3.575V6h2v8.175l3.6-3.575L18 12Z");
}

</style>
