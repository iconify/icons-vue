<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="cso4n_b1m"/><path class="l5yubrbyg"/><path class="ahegroxpb"/><path class="c63nwlahm"/><path class="c5uxuiudu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-guyana" /></template>
<style>
.ahegroxpb {
  fill: var(--svg-color--fcd116, #FCD116);
  d: path("M3.168 28.712L32.5 18L3.168 7.288z");
}

.c5uxuiudu {
  fill: var(--svg-color--ce1126, #CE1126);
  d: path("M.577 6.93l-.001.002A3.975 3.975 0 0 0 0 9v18c0 .757.229 1.453.594 2.057L16 18L.577 6.93z");
}

.c63nwlahm {
  fill: var(--svg-color--141414, #141414);
  d: path("M18 18L3.168 7.288l-1.8-1.3c-.31.271-.577.589-.791.942l.018 22.126c.214.354.463.684.773.955l1.8-1.3L18 18z");
}

.cso4n_b1m {
  fill: var(--svg-color--009e49, #009E49);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

.l5yubrbyg {
  fill: var(--svg-color--fff, #FFF);
  d: path("M1.808 5.654a3.978 3.978 0 0 0-.44.334v24.024c.139.121.286.233.441.335L36 18L1.808 5.654c.001-.001 0-.001 0 0z");
}

</style>
