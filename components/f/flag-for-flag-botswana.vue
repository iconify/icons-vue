<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u5k796b2q"/><path class="w_9i5bbcb"/><path class="qkxh0ibfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-botswana" /></template>
<style>
.qkxh0ibfx {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M2 32c0 1.7.1 3.4.4 5h59.2c.3-1.6.4-3.3.4-5s-.1-3.4-.4-5H2.4c-.3 1.6-.4 3.3-.4 5");
}

.u5k796b2q {
  fill: var(--svg-color--b4d7ee, #b4d7ee);
  d: path("M60.9 24C57.4 11.3 45.8 2 32 2S6.6 11.3 3.1 24v16C6.6 52.7 18.2 62 32 62s25.4-9.3 28.9-22z");
}

.w_9i5bbcb {
  fill: var(--svg-color--fff, #fff);
  d: path("M61.6 27c-.2-1-.4-2-.7-3H3.1c-.3 1-.5 2-.7 3zM2.4 37c.2 1 .4 2 .7 3h57.8c.3-1 .5-2 .7-3z");
}

</style>
