<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyojnkbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fitbit-check-small-rounded" /></template>
<style>
.fyojnkbiz {
  fill: currentColor;
  d: path("m10.5 13.4l4.9-4.9q.275-.275.7-.275t.7.275q.275.275.275.7t-.275.7l-5.6 5.6q-.3.3-.7.3t-.7-.3l-2.6-2.6q-.275-.275-.275-.7t.275-.7q.275-.275.7-.275t.7.275l1.9 1.9Z");
}

</style>
