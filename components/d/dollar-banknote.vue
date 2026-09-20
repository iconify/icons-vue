<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t8s5tvbsi"/><path class="jzp-q1iau"/><circle class="anu8-fb2w"/><path class="qnigidcgb"/><path class="dda_ai0uw"/><path class="rfa2p5b0x"/><path class="qm0ssrb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:dollar-banknote" /></template>
<style>
.anu8-fb2w {
  cx: 25px;
  cy: 18px;
  r: 6.5px;
  fill: var(--svg-color--77b255, #77b255);
}

.dda_ai0uw {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M14 6h8v24.062h-8z");
}

.jzp-q1iau {
  fill: var(--svg-color--a7d28b, #a7d28b);
  d: path("M2 6C0 6 0 8 0 8v20s0 2 2 2h32c2 0 2-2 2-2V8s0-2-2-2z");
}

.qm0ssrb7m {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M11.81 20.023c0-2.979-5.493-2.785-5.493-4.584c0-.871.833-1.296 1.799-1.296c1.625 0 1.914 1.044 2.65 1.044c.521 0 .772-.328.772-.696c0-.856-1.296-1.502-2.539-1.726v-.825a.932.932 0 1 0-1.864 0v.853c-1.354.31-2.521 1.25-2.521 2.781c0 2.862 5.493 2.746 5.493 4.758c0 .695-.754 1.391-1.992 1.391c-1.857 0-2.476-1.257-3.229-1.257c-.368 0-.696.309-.696.775c0 .741 1.24 1.631 2.947 1.881l-.001.004v.934a.933.933 0 0 0 1.864 0v-.934c0-.01-.005-.019-.006-.028c1.535-.287 2.816-1.286 2.816-3.075");
}

.qnigidcgb {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M33 28.5H3c-.827 0-1.5-.673-1.5-1.5V9c0-.827.673-1.5 1.5-1.5h30c.827 0 1.5.673 1.5 1.5v18c0 .827-.673 1.5-1.5 1.5M3 8.5a.5.5 0 0 0-.5.5v18c0 .275.225.5.5.5h30c.275 0 .5-.225.5-.5V9a.5.5 0 0 0-.5-.5z");
}

.rfa2p5b0x {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M14 30h8v6h-8z");
}

.t8s5tvbsi {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M2 11c-2 0-2 2-2 2v21s0 2 2 2h32c2 0 2-2 2-2V13s0-2-2-2z");
}

</style>
