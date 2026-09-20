<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="hsenq4n8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-week-start-28-filled" /></template>
<style>
.hsenq4n8s {
  fill: currentColor;
  d: path("M6.25 25A3.25 3.25 0 0 1 3 21.75V6.25A3.25 3.25 0 0 1 6.25 3h15.5A3.25 3.25 0 0 1 25 6.25v15.5A3.25 3.25 0 0 1 21.75 25zm2.5-5.25a.75.75 0 0 0 .743-.648L9.5 19V9l-.007-.102a.75.75 0 0 0-1.486 0L8 9v10l.007.102a.75.75 0 0 0 .743.648");
}

</style>
