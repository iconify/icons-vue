<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="h19joibfb"/><path class="l6_9mcblb"/><path class="q977db4lh"/><circle class="l0iqzbctr"/><circle class="vitr-xl6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:kitchen-knife" /></template>
<style>
.h19joibfb {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M35.875 34.604L19.796 15.113s-5.637 3.692-7.689 9.676c0 0 4.667 5.292 9.79 8.225c6.368 3.646 11.642 2.855 13.703 2.391a.496.496 0 0 0 .275-.801");
}

.l0iqzbctr {
  cx: 11.618px;
  cy: 10.543px;
  r: 1.365px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

.l6_9mcblb {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("m18.071 13.005l-4.035 3.559c.066.028.316.45.174 1.107c-.402 1.865-2.346 4.288-2.974 5.098c-.194.25-.224.691.026 1.007l.845 1.013c1.821-3.964 6.556-8.694 7.689-9.676z");
}

.q977db4lh {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M18.071 13.005s-3.32-4.216-5.763-6.986S8.208 1.658 6.625.64C5.01-.398 3.285.205 1.981 1.354S-.722 5.082.787 6.793c.826.937 2.785.078 3.791 1.219c.683.774 1.031 1.365 3.464 3.859c3.759 3.854 5.994 4.692 5.994 4.692s1.251-1.042 1.932-1.648a222 222 0 0 0 2.103-1.91");
}

.vitr-xl6s {
  cx: 5.903px;
  cy: 4.653px;
  r: 1.365px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

</style>
