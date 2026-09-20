<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="yb5z19bsg"/><path class="is9vgxh9p"/><path class="xpy8sjkzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-italy" /></template>
<style>
.is9vgxh9p {
  fill: var(--svg-color--009246, #009246);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5z");
}

.xpy8sjkzl {
  fill: var(--svg-color--eee, #eee);
  d: path("M12 5h12v26H12z");
}

.yb5z19bsg {
  fill: var(--svg-color--ce2b37, #ce2b37);
  d: path("M36 27a4 4 0 0 1-4 4h-8V5h8a4 4 0 0 1 4 4z");
}

</style>
