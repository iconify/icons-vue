<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="w2giw2buu"/><ellipse class="lydwu6q9h"/><path class="l77a27bxd"/><path class="nz58l_bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-blowing-a-kiss" /></template>
<style>
.l77a27bxd {
  fill: var(--svg-color--f46767, #f46767);
  d: path("M61.4 42.6c-.9-1.8-2.7-3-5-2.8s-4.1 1.4-5.6 3.5c-1.5-2-3.3-3.3-5.6-3.4s-4.1 1.1-5 2.9s-.9 4.2.9 7c1.8 2.7 9.5 8.2 9.7 8.4c.2-.2 7.9-5.8 9.7-8.4c1.8-3 1.8-5.4.9-7.2");
}

.lydwu6q9h {
  cx: 22px;
  cy: 27px;
  fill: var(--svg-color--664e27, #664e27);
  rx: 5px;
  ry: 6px;
}

.nz58l_bbs {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M51.9 30.5c-1.9-4.1-4.7-6.1-7.5-6.1s-5.6 2-7.5 6.1c-.2.4.8 1.2 1.3.8c1.8-1.5 4-2.1 6.2-2.1s4.4.6 6.2 2.1c.5.4 1.4-.3 1.3-.8M39.5 50.4c1.6-1.6-1.8-3-1.8-5.9s3.4-4.2 1.8-5.9c-1.9-2-6-.5-8.6-3.1c0 2.2 1.8 4.5 5.2 4.5c0 0-2.3.9-2.3 4.5s2.3 4.5 2.3 4.5c-3.4 0-5.2 2.3-5.2 4.5c2.6-2.7 6.7-1.2 8.6-3.1");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.w2giw2buu {
  fill: var(--svg-color--f46767, #f46767);
  d: path("M50.9 58h-.1z");
}

</style>
