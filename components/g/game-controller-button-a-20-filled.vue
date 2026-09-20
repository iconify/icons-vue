<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="smqvw0tbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:game-controller-button-a-20-filled" /></template>
<style>
.smqvw0tbv {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m0 3.5a.5.5 0 0 0-.43.246l-.034.068l-3 7.5a.5.5 0 1 0 .928.371l.884-2.211a.5.5 0 0 0 .152.026h3.143l.018-.002l.875 2.188a.5.5 0 1 0 .928-.371l-3-7.5A.5.5 0 0 0 10 5.5m1.262 5H8.738L10 7.345z");
}

</style>
