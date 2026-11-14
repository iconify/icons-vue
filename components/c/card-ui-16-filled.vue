<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a2ax2dbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:card-ui-16-filled" /></template>
<style>
.a2ax2dbad {
  fill: currentColor;
  d: path("M12.5 3A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 1 10.5v-5A2.5 2.5 0 0 1 3.5 3zM3.75 9a.75.75 0 0 0-.75.75v.5c0 .414.336.75.75.75h3.5a.75.75 0 0 0 .75-.75v-.5A.75.75 0 0 0 7.25 9zM3.5 7a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zm0-2a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1z");
}

</style>
