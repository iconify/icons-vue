<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1q2jjbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:1x-mobiledata-outline-rounded" /></template>
<style>
.h1q2jjbbe {
  fill: currentColor;
  d: path("M6.5 8.5H5q-.213 0-.356-.144T4.5 7.999t.144-.356T5 7.5h2q.213 0 .356.144T7.5 8v8q0 .213-.144.356t-.357.144t-.356-.144T6.5 16zm8.15 4.189l-2.129 3.567q-.063.116-.17.18t-.247.064q-.29 0-.434-.25t.003-.5l2.404-4.05l-2.079-3.425q-.165-.27-.013-.522q.151-.253.455-.253q.145 0 .26.069t.177.181l1.812 2.962l1.784-2.968q.063-.115.175-.18q.113-.064.25-.064q.289 0 .432.25t-.003.5l-2.054 3.45l2.385 4.025q.165.27.002.522q-.162.253-.457.253q-.135 0-.252-.069t-.178-.181z");
}

</style>
