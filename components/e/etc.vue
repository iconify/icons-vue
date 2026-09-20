<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z49htiefw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:etc" /></template>
<style>
.z49htiefw {
  fill: var(--svg-color--01c853, #01c853);
  d: path("m6.577 11.063l5.476-2.235l5.294 2.295L12.037 3zm.015 2.482l5.46 3.075l5.573-3.075L12.105 21zm5.476-3.623l5.542 2.393l-5.542 3l-5.693-3.067l5.7-2.326z");
}

</style>
