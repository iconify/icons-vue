<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g5i537bxa"/><path class="kw460ilrd"/><path class="uoe6jwbnn"/><path class="pgt4xskez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-lesotho" /></template>
<style>
.g5i537bxa {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M2 32c0 5.9 1.7 11.4 4.6 16h50.7c2.9-4.6 4.6-10.1 4.6-16s-1.7-11.4-4.6-16H6.6C3.7 20.6 2 26.1 2 32");
}

.kw460ilrd {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M57.4 16C52.1 7.6 42.7 2 32 2S11.9 7.6 6.6 16z");
}

.pgt4xskez {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M35.1 30.8c.9-1.1 1.4-2.7 1.4-4.5c0-3.5-2-6.2-4.5-6.2s-4.5 2.7-4.5 6.2c0 1.8.5 3.4 1.4 4.5l-6.9 8s0 5.3 10 5.3s10-5.3 10-5.3zm-.4-4.6c0 1.2-.3 2.3-.8 3.1l-1.5-1.7V26l1.4-.7l-1.4-.7v-2.8c1.3.4 2.3 2.3 2.3 4.4m-5.4 0c0-2.2 1-4 2.3-4.4v2.8l-1.4.7l1.4.7v1.6l-1.5 1.7c-.5-.8-.8-1.9-.8-3.1");
}

.uoe6jwbnn {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M6.6 48c5.3 8.4 14.7 14 25.4 14s20.1-5.6 25.4-14z");
}

</style>
