<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5hm3zqqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:crown-subtract-24-filled" /></template>
<style>
.p5hm3zqqd {
  fill: currentColor;
  d: path("M13.457 6.37a2 2 0 1 0-2.913 0L7.918 9.65a.25.25 0 0 1-.307.068l-2.65-1.326A2 2 0 1 0 2.556 9.95l1.804 9.623A1.75 1.75 0 0 0 6.08 21h5.942a6.5 6.5 0 0 1 9.028-8.946l.394-2.104a2 2 0 1 0-2.405-1.558l-2.651 1.326a.25.25 0 0 1-.307-.068zM23 17.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-9 0a.5.5 0 0 0 .5.5h6a.5.5 0 0 0 0-1h-6a.5.5 0 0 0-.5.5");
}

</style>
