<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="d5hz59b-e"/><path class="ay78w6zvs"/><path class="j0key6b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:disappointed-face" /></template>
<style>
.ay78w6zvs {
  fill: var(--svg-color--917524, #917524);
  d: path("M22.7 19.8c-2.7 3.3-9.2 6.3-13.5 6.3c-.6 0-.7 2.2 0 2.2c4.9 0 12-3.3 15.2-7.1c.5-.5-1.3-1.8-1.7-1.4m18.6 0c2.7 3.3 9.2 6.3 13.5 6.3c.6 0 .7 2.2 0 2.2c-4.9 0-12-3.3-15.2-7.1c-.5-.5 1.3-1.8 1.7-1.4");
}

.d5hz59b-e {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M25.5 28.4c1.4 2.9-.4 6.6-3.9 8.3c-3.5 1.6-7.5.6-8.9-2.3c-.8-1.9 12-7.9 12.8-6m13 0c-1.4 2.9.4 6.6 3.9 8.3c3.5 1.6 7.5.6 8.9-2.3c.8-1.9-12-7.9-12.8-6");
}

.j0key6b1a {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M40.6 46.4c-5.4-2.5-11.8-2.5-17.2 0c-1.3.6.3 4.2 1.7 3.5c3.6-1.7 8.9-2.3 13.9 0c1.3.6 3-2.8 1.6-3.5");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
