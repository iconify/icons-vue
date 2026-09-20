<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ym63cqm5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:letter-h" /></template>
<style>
.ym63cqm5v {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M109.48 16.34H84.84c-1.28 0-2.33 1.04-2.33 2.33v36.27H45.5V18.68c0-1.29-1.04-2.33-2.34-2.33H18.53a2.34 2.34 0 0 0-2.34 2.33v99.96c0 1.29 1.05 2.33 2.34 2.33h24.63a2.34 2.34 0 0 0 2.34-2.33V76.15h37.02v42.48c0 1.29 1.05 2.33 2.33 2.33h24.64c1.29 0 2.33-1.05 2.33-2.33V18.68a2.35 2.35 0 0 0-2.34-2.34");
}

</style>
