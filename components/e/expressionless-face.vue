<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><path class="n4k65qesx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:expressionless-face" /></template>
<style>
.n4k65qesx {
  fill: var(--svg-color--664500, #664500);
  d: path("M25 26H11a1 1 0 1 1 0-2h14a1 1 0 1 1 0 2m-10-8H8a1 1 0 0 1 0-2h7a1 1 0 0 1 0 2m13 0h-7a1 1 0 1 1 0-2h7a1 1 0 1 1 0 2");
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

</style>
