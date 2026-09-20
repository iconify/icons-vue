<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jwx24k-ui"/><path class="bhnanmb-o"/><path class="lzs7d0blo"/><path class="eusdqy1ta"/><path class="kx7nalbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-guyana" /></template>
<style>
.bhnanmb-o {
  fill: var(--svg-color--fff, #fff);
  d: path("M1.808 5.654a4 4 0 0 0-.44.334v24.024q.209.182.441.335L36 18zq0-.002 0 0");
}

.eusdqy1ta {
  fill: var(--svg-color--141414, #141414);
  d: path("M18 18L3.168 7.288l-1.8-1.3c-.31.271-.577.589-.791.942l.018 22.126c.214.354.463.684.773.955l1.8-1.3z");
}

.jwx24k-ui {
  fill: var(--svg-color--009e49, #009e49);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.kx7nalbwg {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("m.577 6.93l-.001.002A4 4 0 0 0 0 9v18c0 .757.229 1.453.594 2.057L16 18z");
}

.lzs7d0blo {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M3.168 28.712L32.5 18L3.168 7.288z");
}

</style>
