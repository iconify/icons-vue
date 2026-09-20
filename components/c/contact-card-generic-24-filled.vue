<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2q6mpnfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contact-card-generic-24-filled" /></template>
<style>
.r2q6mpnfr {
  fill: currentColor;
  d: path("M19.75 4A2.25 2.25 0 0 1 22 6.25v11.5A2.25 2.25 0 0 1 19.75 20H4.25A2.25 2.25 0 0 1 2 17.75V6.25A2.25 2.25 0 0 1 4.25 4zM8 9a3 3 0 1 0 0 6a3 3 0 0 0 0-6m5.25 4a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5zM8 10.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m5.25-1a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5z");
}

</style>
