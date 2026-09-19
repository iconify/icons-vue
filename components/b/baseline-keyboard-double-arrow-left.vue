<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks5tz3pyn"/><path class="tlp7y7bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-keyboard-double-arrow-left" /></template>
<style>
.ks5tz3pyn {
  fill: currentColor;
  d: path("M17.59 18L19 16.59L14.42 12L19 7.41L17.59 6l-6 6z");
}

.tlp7y7bro {
  fill: currentColor;
  d: path("m11 18l1.41-1.41L7.83 12l4.58-4.59L11 6l-6 6z");
}

</style>
