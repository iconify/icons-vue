<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="hdhpr4b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:kissing-face-with-smiling-eyes" /></template>
<style>
.hdhpr4b6j {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M29 26.6c-2.7-4.7-5.9-6.7-8.7-6.3s-5.1 3.5-6 8.8c-.1.5 1 1.3 1.4.7c1.4-2.2 3.4-3.3 5.7-3.7c2.2-.4 4.5 0 6.6 1.5c.5.6 1.3-.5 1-1m21.6-3.8c-2.7-4.7-5.9-6.7-8.7-6.3s-5.1 3.5-6 8.8c-.1.5 1 1.3 1.4.7c1.4-2.2 3.4-3.3 5.7-3.7c2.2-.4 4.5 0 6.6 1.5c.5.6 1.3-.5 1-1m-5 22.6c1.3-1.9-2.3-2.6-2.8-5.5s2.6-4.8.8-6.1c-2.2-1.6-6 .6-9-1.6c.4 2.1 2.6 4.1 5.9 3.5c0 0-2.1 1.3-1.5 4.8s3 4 3 4c-3.3.6-4.7 3.2-4.3 5.3c2-2.8 6.4-2.1 7.9-4.4");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
