<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="om-uru34q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-down-20-filled" /></template>
<style>
.om-uru34q {
  fill: currentColor;
  d: path("M17.25 4a.75.75 0 0 1 .75.75A7.25 7.25 0 0 1 10.75 12H4.56l3.22 3.22a.75.75 0 1 1-1.06 1.06l-4.5-4.5a.75.75 0 0 1 0-1.06l4.5-4.5a.75.75 0 0 1 1.06 1.06L4.56 10.5h6.19a5.75 5.75 0 0 0 5.75-5.75a.75.75 0 0 1 .75-.75");
}

</style>
