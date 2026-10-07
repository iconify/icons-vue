<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsn0_fc-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:braces-fill" /></template>
<style>
.qsn0_fc-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 2C6.8954 2 6 2.8954 6 4L6 8.9645C6 9.4949 5.7893 10.0036 5.4142 10.3787L4.1464 11.6464C4.0527 11.7402 4 11.8674 4 12C4 12.1326 4.0527 12.2598 4.1464 12.3536L5.4142 13.6213C5.7893 13.9964 6 14.5051 6 15.0355L6 20C6 21.1046 6.8954 22 8 22M16 2C17.1046 2 18 2.8954 18 4L18 8.9645C18 9.4949 18.2107 10.0036 18.5858 10.3787L19.8536 11.6464C19.9473 11.7402 20 11.8674 20 12C20 12.1326 19.9473 12.2598 19.8536 12.3536L18.5858 13.6213C18.2107 13.9964 18 14.5051 18 15.0355L18 20C18 21.1046 17.1046 22 16 22");
}

</style>
