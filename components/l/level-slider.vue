<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rj-4scb3k"/><path class="xsmq6lbhf"/><path class="l1qpcyd-e"/><path class="uuszz8bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:level-slider" /></template>
<style>
.l1qpcyd-e {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M15 6a1 1 0 0 1-1 1h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 1 1m0 12a1 1 0 0 1-1 1h-4a1 1 0 1 1 0-2h4a1 1 0 0 1 1 1m0 12a1 1 0 0 1-1 1h-4a1 1 0 1 1 0-2h4a1 1 0 0 1 1 1M27 6a1 1 0 0 1-1 1h-4a1 1 0 1 1 0-2h4a1 1 0 0 1 1 1m0 12a1 1 0 0 1-1 1h-4a1 1 0 1 1 0-2h4a1 1 0 0 1 1 1m0 12a1 1 0 0 1-1 1h-4a1 1 0 1 1 0-2h4a1 1 0 0 1 1 1m-12-5.894c0 .494-.4.894-.893.894h-2.214a.893.893 0 0 1-.893-.894v-.213c0-.493.4-.893.893-.893h2.214c.493 0 .893.4.893.894zm10 0c0 .494-.4.894-.893.894h-2.215a.893.893 0 0 1-.892-.894v-.213c0-.493.4-.893.893-.893h2.215c.492 0 .892.4.892.894z");
}

.rj-4scb3k {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M33 32a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h22a4 4 0 0 1 4 4z");
}

.uuszz8bzu {
  fill: var(--svg-color--269, #269);
  d: path("M25 13a2 2 0 0 1-2 2H13a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2z");
}

.xsmq6lbhf {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M19 31a1 1 0 1 1-2 0V5a1 1 0 0 1 2 0z");
}

</style>
