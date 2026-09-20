<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ugg4ue1la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-double-down-20-filled" /></template>
<style>
.ugg4ue1la {
  fill: currentColor;
  d: path("M14.72 9.97a.75.75 0 1 1 1.06 1.06l-5.25 5.25a.75.75 0 0 1-1.06 0l-5.25-5.25a.75.75 0 1 1 1.06-1.06L10 14.69zm0-5.5a.75.75 0 1 1 1.06 1.06l-5.25 5.25a.75.75 0 0 1-1.06 0L4.22 5.53a.75.75 0 1 1 1.06-1.06L10 9.19z");
}

</style>
