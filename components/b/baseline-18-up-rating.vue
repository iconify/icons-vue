<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fke3nsb4z"/><path class="ea7ut7bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-18-up-rating" /></template>
<style>
.ea7ut7bfr {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-9 12H8.5v-4.5H7V9h3zm6-1c0 .55-.45 1-1 1h-2.5c-.55 0-1-.45-1-1v-4c0-.55.45-1 1-1H15c.55 0 1 .45 1 1z");
}

.fke3nsb4z {
  fill: currentColor;
  d: path("M13 12.5h1.5V14H13zm0-2.5h1.5v1.5H13z");
}

</style>
