<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGNMD8BbSm)" class="vsm3r-bnc"/><defs><linearGradient id="SVGNMD8BbSm" x1="17.59" x2="6.929" y1="5.195" y2="19.354" gradientUnits="userSpaceOnUse"><stop class="mu6yehrol"/><stop offset=".59" class="od5f7ageo"/><stop offset="1" class="zg8kp4hfd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aurora" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mu6yehrol {
  stop-color: var(--svg-color--95e141, #95e141);
}

.od5f7ageo {
  stop-color: var(--svg-color--63b836, #63b836);
}

.vsm3r-bnc {
  d: path("M13.88 5.676a2.1 2.1 0 0 0-3.768 0L4.424 16.46a2.1 2.1 0 0 0 1.884 3.04h11.377a2.1 2.1 0 0 0 1.792-.995a2.1 2.1 0 0 0 .092-2.047zm-4.842-.54a3.3 3.3 0 0 1 5.916 0L20.65 15.92a3.3 3.3 0 0 1-2.965 4.782H6.309a3.312 3.312 0 0 1-2.964-4.782L9.038 5.142z");
}

.zg8kp4hfd {
  stop-color: var(--svg-color--409c2d, #409c2d);
}

</style>
