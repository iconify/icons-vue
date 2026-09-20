<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="znigdh2sm"/><path class="q_v8hjb5b"/><path class="g5oryk8cr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eurc" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g5oryk8cr {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--0b53bf, #0b53bf);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-03px, 0.03px);
  d: path("M6.375 12a5.64 5.64 0 0 1 4.005-5.394v-1.16A6.74 6.74 0 0 0 5.25 12a6.74 6.74 0 0 0 5.13 6.553v-1.159A5.63 5.63 0 0 1 6.375 12Zm7.245-6.553v1.159A5.64 5.64 0 0 1 17.625 12a5.64 5.64 0 0 1-4.005 5.394v1.16A6.74 6.74 0 0 0 18.75 12a6.74 6.74 0 0 0-5.13-6.553Z");
}

.q_v8hjb5b {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--0b53bf, #0b53bf);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-03px, 0.03px);
  d: path("M13.913 14.143a3.4 3.4 0 0 1-1.232.248c-.814 0-1.58-.347-1.947-1.181h1.79l.348-.844h-2.346a4 4 0 0 1 0-.732h2.644l.349-.843h-2.785c.367-.835 1.133-1.182 1.947-1.182c.41 0 .838.09 1.232.248l.36-.855a3.4 3.4 0 0 0-1.575-.377c-1.317 0-2.649.736-3.13 2.166h-.864v.843h.69a4 4 0 0 0 0 .732h-.69v.844h.863c.482 1.429 1.814 2.165 3.13 2.165a3.4 3.4 0 0 0 1.576-.377z");
}

.znigdh2sm {
  fill: var(--svg-color--0b53bf, #0b53bf);
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

</style>
