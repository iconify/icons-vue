<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="smhezv8hu"/><path class="n50g81b2t"/><g class="hq2-vcghy"><path class="hn4pyndam"/><path class="u6dqjh8-c"/></g><path class="udd3t81mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-australia" /></template>
<style>
.hn4pyndam {
  d: path("M15.4 14L30 32h2v-4.9L21.4 14z");
}

.hq2-vcghy {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

.n50g81b2t {
  fill: var(--svg-color--fff, #fff);
  d: path("M32 2c-4.7 0-9.1 1.1-13.1 3v6H11v7.9H5c-1.9 4-3 8.4-3 13.1h12V17l12 15h6v-7.5L23.6 14H32z");
}

.smhezv8hu {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M32 2v10H12v20H2c0 16.6 13.4 30 30 30s30-13.4 30-30S48.6 2 32 2");
}

.u6dqjh8-c {
  d: path("M32 5H18.9c-6 2.9-11 7.9-13.9 13.9V32h6V11h21z");
}

.udd3t81mw {
  fill: var(--svg-color--fff, #fff);
  d: path("m8 35.7l2.2-2.7l-.7 3.5l3.5.1l-3.1 1.6L12 41l-3.1-1.4L8 43l-.9-3.4L4 41l2.1-2.8L3 36.6l3.5-.1l-.7-3.5zm44-15.5l1.8-2.2l-.6 2.8l2.8.1l-2.5 1.3l1.7 2.2l-2.5-1.2L52 26l-.7-2.8l-2.5 1.2l1.7-2.2l-2.5-1.3l2.8-.1l-.6-2.8zm0 20l1.8-2.2l-.6 2.8l2.8.1l-2.5 1.3l1.7 2.2l-2.5-1.2L52 46l-.7-2.8l-2.5 1.2l1.7-2.2l-2.5-1.3l2.8-.1l-.6-2.8zm-10-14l1.8-2.2l-.6 2.8l2.8.1l-2.5 1.3l1.7 2.2l-2.5-1.2L42 32l-.7-2.8l-2.5 1.2l1.7-2.2l-2.5-1.3l2.8-.1l-.6-2.8z");
}

</style>
