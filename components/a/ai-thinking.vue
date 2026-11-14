<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y733uhb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ai-thinking" /></template>
<style>
.y733uhb_c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.641 17.859Q5.032 19.25 7 19.25h9.949q1.724.226 3.122-.822q1.419-1.065 1.67-2.822t-.813-3.177q-.854-1.138-2.152-1.526q-.011-2.183-1.457-3.919q-1.664-1.996-4.251-2.231T8.484 6.181q-1.743 1.453-2.143 3.61q-1.548.198-2.7 1.35Q2.25 12.532 2.25 14.5t1.391 3.359M7 12.5Q7 11 8.5 11t1.5 1.5T8.5 14T7 12.5m5-1.5q1.5 0 1.5 1.5T12 14t-1.5-1.5T12 11m2 1.5q0-1.5 1.5-1.5t1.5 1.5t-1.5 1.5t-1.5-1.5");
}

</style>
