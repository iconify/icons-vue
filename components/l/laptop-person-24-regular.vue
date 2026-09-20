<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqcy_pbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-person-24-regular" /></template>
<style>
.uqcy_pbbl {
  fill: currentColor;
  d: path("M6.25 4A2.25 2.25 0 0 0 4 6.25v7.5A2.25 2.25 0 0 0 6.25 16h9.8a3.5 3.5 0 0 1-.905-1.5H6.25a.75.75 0 0 1-.75-.75v-7.5a.75.75 0 0 1 .75-.75h11.5a.75.75 0 0 1 .75.75V10c.537 0 1.045.12 1.5.337V6.25A2.25 2.25 0 0 0 17.75 4zm-3.5 13.5h10.558A2.76 2.76 0 0 0 13 18.772v.103q0 .063.002.125H2.75a.75.75 0 0 1 0-1.5m18.25-4a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m2 5.375C23 20.431 21.714 22 18.5 22S14 20.437 14 18.875v-.103c0-.98.794-1.772 1.773-1.772h5.454c.98 0 1.773.793 1.773 1.772z");
}

</style>
