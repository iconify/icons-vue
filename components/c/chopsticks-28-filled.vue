<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="c4_dr3r7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chopsticks-28-filled" /></template>
<style>
.c4_dr3r7h {
  fill: currentColor;
  d: path("M5.351 2.115a.75.75 0 0 1 1.034.236l6.687 10.65H16.3l-6.186-9.852a.75.75 0 0 1 1.27-.798l6.687 10.65h7.267a.66.66 0 0 1 .661.66v.34c0 1.035-.131 2.04-.378 3H2.378A12 12 0 0 1 2 14v-.34a.66.66 0 0 1 .661-.66h8.64L5.115 3.148a.75.75 0 0 1 .236-1.034M2.872 18.5C4.652 22.898 8.964 26 14 26s9.348-3.102 11.128-7.5z");
}

</style>
