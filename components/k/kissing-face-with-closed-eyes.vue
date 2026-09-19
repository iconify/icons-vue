<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="ys06cm0bx"/><path class="b6ofs-otj"/><path class="scp8y9j7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:kissing-face-with-closed-eyes" /></template>
<style>
.b6ofs-otj {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M55 20.9c-4.2-1-8.2.4-9 3.2s1.9 6 6.1 7s8.2-.4 9-3.2s-2-5.9-6.1-7m-33.1 8.8c-2.4-2.9-8.3-3-13.1-.2C4 32.4 2 37.1 4.5 40c2.4 2.9 8.3 3 13.1.2s6.7-7.5 4.3-10.5");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.scp8y9j7r {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M35.2 17.7c5.5 7.1 13.9 5.6 16.7-2.9c.1-.4-.4-.5-1.2-.8c-3.6 4-10.4 4.9-14.7 2.6c-.6.4-1.1.7-.8 1.1M10.8 22c5.5 7.1 13.9 5.6 16.7-2.9c.1-.4-.4-.5-1.2-.8c-3.6 4-10.4 4.9-14.7 2.6c-.6.4-1.1.7-.8 1.1");
}

.ys06cm0bx {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M45.6 45.4c1.3-1.9-2.3-2.6-2.8-5.5s2.6-4.8.8-6.1c-2.2-1.6-6 .6-9-1.6c.4 2.1 2.6 4.1 5.9 3.5c0 0-2.1 1.3-1.5 4.8s3 4 3 4c-3.3.6-4.7 3.2-4.3 5.3c2-2.8 6.4-2.1 7.9-4.4");
}

</style>
