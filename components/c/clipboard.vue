<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hc-r9xwvw"/><path class="yzh1g_mfa"/><path class="oehyetk6t"/><path class="a6z53szyf"/><path class="ot1iitbis"/><path class="sew282b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:clipboard" /></template>
<style>
.a6z53szyf {
  fill: var(--svg-color--333, #333);
  d: path("m46.8 11.1l-7.5-3.4l1.9-2.8c.4-.6 1.2-.8 1.9-.5l5 2.2c.7.3 1 1.1.6 1.6z");
}

.hc-r9xwvw {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M35.7 62.2c-1.4 2.1-4.4 2.4-6.8.7l-27-19C.1 42.6-.5 40.1.7 38.3L24.4 2C25.6.2 28.2-.5 30.3.4l30.6 13.5c2.7 1.2 3.9 3.9 2.5 6z");
}

.oehyetk6t {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M49 14.8c-.4.6-1.3.8-2.1.4L35.3 9.7c-.7-.3-.9-1-.5-1.6l1.8-2.8c.4-.6 1.2-.8 1.9-.5l11.9 5.3c.8.3 1 1.1.7 1.7z");
}

.ot1iitbis {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("m47.3 26.6l-15.6-8.1l.8-1.2l15.7 7.9zm-20.6-8.9c-.2.1-.4 0-.4-.1l-1-2.8c-.1-.2.1-.4.3-.4l.4-.1c.2 0 .4.1.5.2L27 16c.1.2.3.2.4.1l2.9-1.6c.2-.1.4-.1.5.1l.2.3c.1.2.1.4-.1.5z");
}

.sew282b_n {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("m42.2 34.4l-15.4-8.5l.9-1.3l15.4 8.5zm-18.3-8.2l-4.5-2.6l2.6-4l4.6 2.5zm13.2 16l-15.1-9l.9-1.2L38 40.9zm-18-8.7l-4.4-2.7l2.6-4l4.5 2.6zM32 50.1l-14.8-9.5l.8-1.3l14.8 9.4zm-17.6-9.3L10 37.9l2.6-4l4.4 2.8z");
}

.yzh1g_mfa {
  fill: var(--svg-color--fff, #fff);
  d: path("M31.4 59.8L3.5 40.7L28 3.3l31.1 14.2z");
}

</style>
