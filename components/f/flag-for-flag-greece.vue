<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ynqb-xb9p"/><path class="bsfxj5bku"/><path class="tdr7eqtty"/><path class="ug2l32bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-greece" /></template>
<style>
.bsfxj5bku {
  fill: var(--svg-color--eee, #eee);
  d: path("M8.5 19.5H0V22h36v-2.5H14zM0 27q.002.255.035.5h35.931q.032-.245.034-.5v-2H0zm14-13h22v2.5H14zm0-5.5V11h22V9q-.002-.255-.035-.5z");
}

.tdr7eqtty {
  fill: var(--svg-color--0d5eb0, #0d5eb0);
  d: path("M14 11h22v3H14zM0 22h36v3H0zm2.065 8.5h31.87a4 4 0 0 0 2.031-3H.035a4 4 0 0 0 2.03 3M0 14h5.5v5.5H0zm14 2.5V14H8.5v5.5H36v-3zm19.935-11A4 4 0 0 0 32 5H4A4 4 0 0 0 .034 8.5C.014 8.664 0 8.83 0 9v2h5.5V5.5h3V11H14V8.5h21.965a4 4 0 0 0-2.03-3");
}

.ug2l32bxg {
  fill: var(--svg-color--eee, #eee);
  d: path("M8.5 11V5h-3v6H0v3h5.5v5.5h3V14H14v-3z");
}

.ynqb-xb9p {
  fill: var(--svg-color--0d5eb0, #0d5eb0);
  d: path("M4 31h28a4 4 0 0 0 1.935-.5H2.065A4 4 0 0 0 4 31");
}

</style>
