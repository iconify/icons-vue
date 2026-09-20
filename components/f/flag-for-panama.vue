<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rbi7-ngam"/><path class="ln1xg-mcz"/><path class="vqw07-giz"/><path class="x_r1_q5wc"/><path class="kn406fu5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-panama" /></template>
<style>
.kn406fu5r {
  fill: var(--svg-color--d21034, #D21034);
  d: path("M25.91 24.854l-.673 2.073L27 25.646l1.763 1.281l-.673-2.073l1.763-1.281h-2.179L27 21.5l-.674 2.073h-2.179z");
}

.ln1xg-mcz {
  fill: var(--svg-color--005293, #005293);
  d: path("M18 18v13H4a4 4 0 0 1-4-4v-9h18z");
}

.rbi7-ngam {
  fill: var(--svg-color--eee, #EEE);
  d: path("M18 18V5H4a4 4 0 0 0-4 4v9h18zm0 0v13h14a4 4 0 0 0 4-4v-9H18z");
}

.vqw07-giz {
  fill: var(--svg-color--d21034, #D21034);
  d: path("M18 18V5h14a4 4 0 0 1 4 4v9H18z");
}

.x_r1_q5wc {
  fill: var(--svg-color--005293, #005293);
  d: path("M9.674 10.573L9 8.5l-.674 2.073H6.147l1.763 1.281l-.673 2.073L9 12.646l1.763 1.281l-.673-2.073l1.763-1.281z");
}

</style>
