<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9b4kcb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-24-regular" /></template>
<style>
.f9b4kcb8z {
  fill: currentColor;
  d: path("M3 3.748a.75.75 0 0 1 .75-.75h16.504a.75.75 0 0 1 .6 1.2L16.69 9.75l4.164 5.551a.75.75 0 0 1-.6 1.2H4.5v4.75a.75.75 0 0 1-.648.743L3.75 22a.75.75 0 0 1-.743-.648L3 21.25zm15.754.75H4.5v10.503h14.254l-3.602-4.802a.75.75 0 0 1 0-.9z");
}

</style>
