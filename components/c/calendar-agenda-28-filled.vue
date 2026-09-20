<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="lh-9hi2fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-28-filled" /></template>
<style>
.lh-9hi2fz {
  fill: currentColor;
  d: path("M25 21.75A3.25 3.25 0 0 1 21.75 25H6.25A3.25 3.25 0 0 1 3 21.75V6.25A3.25 3.25 0 0 1 6.25 3h15.5A3.25 3.25 0 0 1 25 6.25zM19.75 14a.75.75 0 0 0-.648-.743L19 13.25H9l-.102.007a.75.75 0 0 0 0 1.486L9 14.75h10l.102-.007A.75.75 0 0 0 19.75 14m0 5.25a.75.75 0 0 0-.648-.743L19 18.5H9l-.102.007a.75.75 0 0 0 0 1.486L9 20h10l.102-.007a.75.75 0 0 0 .648-.743m0-10.5a.75.75 0 0 0-.648-.743L19 8H9l-.102.007a.75.75 0 0 0 0 1.486L9 9.5h10l.102-.007a.75.75 0 0 0 .648-.743");
}

</style>
