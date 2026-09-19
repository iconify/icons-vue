<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><path class="miryn0bnn"/><circle class="ry06sibgd"/><circle class="xrvu5hbnt"/></g><path class="oy_rjm-fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:grimacing-face" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.miryn0bnn {
  d: path("M52.5 40c-2.2-3.6-7.7-6-20.5-6s-18.3 2.4-20.5 6c-1.2 1.9.5 5 .5 5c2.1 3.9 1.8 5 20 5c18.1 0 17.9-1.1 20-5c0 0 1.7-3.1.5-5");
}

.oy_rjm-fd {
  fill: var(--svg-color--fff, #fff);
  d: path("M48 40c.1-.5-.2-1.2-.6-1.5c0 0-3.9-2.5-15.4-2.5s-15.4 2.5-15.4 2.5c-.4.3-.7.9-.6 1.5l.2 1c.1.5.6 1 1.1 1h29.3c.5 0 1-.4 1.1-1zm-16 8c6.3 0 15.2 0 15-2.1c0-.4-.1-.8-.3-1.3s-.3-.7-1.4-.7H18.6c-1.1 0-1.2.1-1.4.7c-.1.5-.2.9-.3 1.3C16.8 48 25.7 48 32 48");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.ry06sibgd {
  cx: 20.5px;
  cy: 24.5px;
  r: 5px;
}

.xrvu5hbnt {
  cx: 43.5px;
  cy: 24.5px;
  r: 5px;
}

</style>
