<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGfaBQpeoC" cx="68.884" cy="124.296" r="70.587" gradientTransform="rotate(-179.751 65.907 -39.816)scale(1 -1.64082)" gradientUnits="userSpaceOnUse"><stop offset=".314" class="wb84icb0c"/><stop offset=".662" class="kfnw9xbpb"/><stop offset=".972" class="ai1a8abib"/></radialGradient><path fill="url(#SVGfaBQpeoC)" class="v4y-3vb4j"/><radialGradient id="SVGVfNAiblG" cx="64.921" cy="54.062" r="73.86" gradientTransform="rotate(90.579 18.654 7.312)scale(1 -.7525)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="md120d8ra"/><stop offset=".328" class="zljevn_fm"/><stop offset=".487" class="m8jhawn2g"/><stop offset=".672" class="b8obylblo"/><stop offset=".793" class="g-c7tbctu"/><stop offset=".822" class="macgdnbtm"/><stop offset=".863" class="qw1jvvbgq"/><stop offset=".91" class="c5nf3fbho"/><stop offset=".941" class="z361i3b5r"/></radialGradient><path fill="url(#SVGVfNAiblG)" class="g7uwg_mcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:fire" /></template>
<style>
.ai1a8abib {
  stop-color: var(--svg-color--f44336, #f44336);
}

.b8obylblo {
  stop-color: var(--svg-color--fff7ad, #fff7ad);
}

.c5nf3fbho {
  stop-color: var(--svg-color--fff38d, #fff38d);
  stop-opacity: 0.209;
}

.g-c7tbctu {
  stop-color: var(--svg-color--fff9c4, #fff9c4);
}

.g7uwg_mcn {
  d: path("M76.11 77.42c-9.09-11.7-5.02-25.05-2.79-30.37c.3-.7-.5-1.36-1.13-.93c-3.91 2.66-11.92 8.92-15.65 17.73c-5.05 11.91-4.69 17.74-1.7 24.86c1.8 4.29-.29 5.2-1.34 5.36c-1.02.16-1.96-.52-2.71-1.23a16.1 16.1 0 0 1-4.44-7.6c-.16-.62-.97-.79-1.34-.28c-2.8 3.87-4.25 10.08-4.32 14.47C40.47 113 51.68 124 65.24 124c17.09 0 29.54-18.9 19.72-34.7c-2.85-4.6-5.53-7.61-8.85-11.88");
}

.kfnw9xbpb {
  stop-color: var(--svg-color--ff6d00, #ff6d00);
}

.m8jhawn2g {
  stop-color: var(--svg-color--fff48f, #fff48f);
}

.macgdnbtm {
  stop-color: var(--svg-color--fff8bd, #fff8bd);
  stop-opacity: 0.804;
}

.md120d8ra {
  stop-color: var(--svg-color--fff176, #fff176);
}

.qw1jvvbgq {
  stop-color: var(--svg-color--fff6ab, #fff6ab);
  stop-opacity: 0.529;
}

.v4y-3vb4j {
  d: path("M35.56 40.73c-.57 6.08-.97 16.84 2.62 21.42c0 0-1.69-11.82 13.46-26.65c6.1-5.97 7.51-14.09 5.38-20.18c-1.21-3.45-3.42-6.3-5.34-8.29c-1.12-1.17-.26-3.1 1.37-3.03c9.86.44 25.84 3.18 32.63 20.22c2.98 7.48 3.2 15.21 1.78 23.07c-.9 5.02-4.1 16.18 3.2 17.55c5.21.98 7.73-3.16 8.86-6.14c.47-1.24 2.1-1.55 2.98-.56c8.8 10.01 9.55 21.8 7.73 31.95c-3.52 19.62-23.39 33.9-43.13 33.9c-24.66 0-44.29-14.11-49.38-39.65c-2.05-10.31-1.01-30.71 14.89-45.11c1.18-1.08 3.11-.12 2.95 1.5");
}

.wb84icb0c {
  stop-color: var(--svg-color--ff9800, #ff9800);
}

.z361i3b5r {
  stop-color: var(--svg-color--fff176, #fff176);
  stop-opacity: 0;
}

.zljevn_fm {
  stop-color: var(--svg-color--fff27d, #fff27d);
}

</style>
