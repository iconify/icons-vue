<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e0nokpblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-undo-20-regular" /></template>
<style>
.e0nokpblu {
  fill: currentColor;
  d: path("M5 2.5a.5.5 0 0 0-1 0v4.9a.6.6 0 0 0 .6.6h4.9a.5.5 0 0 0 0-1H5.906l3.473-3.019a4 4 0 0 1 5.248 6.038l-8.172 7.104a.5.5 0 0 0 .656.754l8.172-7.103a5 5 0 0 0-6.56-7.547L5 6.463z");
}

</style>
