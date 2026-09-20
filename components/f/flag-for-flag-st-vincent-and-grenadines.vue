<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="y200r-bqr"/><path class="n3vicab-a"/><path class="bgzlzwbdm"/><path class="j7tqopbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-st-vincent-and-grenadines" /></template>
<style>
.bgzlzwbdm {
  fill: var(--svg-color--fcd116, #FCD116);
  d: path("M9 5h18v26H9z");
}

.j7tqopbrv {
  d: path("M15.833 23.526L18 27.859l2.167-4.333L18 19.193l-2.167 4.333zm-2.708-5.417l2.167 4.333l2.167-4.333l-2.167-4.333l-2.167 4.333zm5.417 0l2.167 4.333l2.167-4.333l-2.167-4.333l-2.167 4.333z");
  fill: var(--svg-color--009e60, #009E60);
}

.n3vicab-a {
  fill: var(--svg-color--0072c6, #0072C6);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h5V5H4z");
}

.y200r-bqr {
  fill: var(--svg-color--009e60, #009E60);
  d: path("M32 5h-5v26h5a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

</style>
