<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t1sifcbhc"/><path class="l1-747bhw"/><path class="kdgdnt0nm"/><path class="ene4v2yhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-aruba" /></template>
<style>
.ene4v2yhk {
  fill: var(--svg-color--f9d616, #f9d616);
  d: path("M0 22.055h36v1.972H0zM0 27c0 .337.054.659.133.972h35.734A4 4 0 0 0 36 27v-1H0z");
}

.kdgdnt0nm {
  fill: var(--svg-color--d21034, #d21034);
  d: path("m5.333 7.252l-.726 2.355l-2.355.726l2.355.727l.726 2.355l.727-2.355l2.355-.727l-2.355-.726z");
}

.l1-747bhw {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.333 6.333l-.942 3.058l-3.057.943l3.057.943l.943 3.057l.943-3.057l3.057-.943l-3.058-.943zm.727 4.727l-.726 2.355l-.727-2.355l-2.355-.726l2.355-.726l.726-2.355l.727 2.354l2.355.726z");
}

.t1sifcbhc {
  fill: var(--svg-color--4189dd, #4189dd);
  d: path("M32 5H4a4 4 0 0 0-4 4v13.055h36V9a4 4 0 0 0-4-4M6.276 11.276l-.943 3.057l-.943-3.057l-3.057-.943L4.39 9.39l.943-3.057l.943 3.057l3.057.943zM4 31h28a3.99 3.99 0 0 0 3.867-3.028H.133A3.99 3.99 0 0 0 4 31m-4-6.972h36V26H0z");
}

</style>
