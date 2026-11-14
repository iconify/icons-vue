<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnw8mzb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:identity-federation" /></template>
<style>
.tnw8mzb_k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75Q8.75 1.75 8.75 5q0 1.778.972 2.583l-3.327 6.239q-.412-.072-.895-.072q-3.25 0-3.25 3.25t3.25 3.25q2.85 0 3.201-2.5h6.598q.351 2.5 3.201 2.5q1.346 0 2.298-.952T21.75 17t-.952-2.298t-2.298-.952q-.483 0-.895.072l-3.327-6.239q.972-.805.972-2.583q0-3.25-3.25-3.25m3.299 14.5H8.701q-.17-1.209-.923-1.833l3.327-6.239q.412.072.895.072t.895-.072l3.327 6.239q-.753.624-.923 1.833");
}

</style>
