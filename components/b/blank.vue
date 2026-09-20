<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGtFUf4d2S)" class="z3isdab9b"/><path fill="url(#SVGRAcmScbh)" class="lntglvccx"/><defs><linearGradient id="SVGtFUf4d2S" x1="6.375" x2="14.811" y1="5.251" y2="20.437" gradientUnits="userSpaceOnUse"><stop class="wjpmzabvz"/><stop offset=".21" class="q1j9onbfh"/><stop offset=".39" class="ibt7x66qo"/><stop offset=".53" class="r_xkoac5f"/><stop offset=".77" class="nwfwfdbpw"/><stop offset="1" class="pmnlsetjd"/></linearGradient><linearGradient id="SVGRAcmScbh" x1="18.467" x2="6.656" y1="5.813" y2="17.062" gradientUnits="userSpaceOnUse"><stop class="x9hl5mork"/><stop offset="1" class="hvza1bbfi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blank" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hvza1bbfi {
  stop-color: var(--svg-color--c7fe02, #c7fe02);
}

.ibt7x66qo {
  stop-color: var(--svg-color--62e700, #62e700);
}

.lntglvccx {
  d: path("M11.999 3.001c-1.48 0-2.88.36-4.106.99a9 9 0 0 0 9.91 14.888A9 9 0 0 0 12 3M8.624 5.813l9.562 2.812l-1.407 8.156l-9.561-2.531z");
}

.nwfwfdbpw {
  stop-color: var(--svg-color--142417, #142417);
}

.pmnlsetjd {
  stop-color: var(--svg-color--406925, #406925);
}

.q1j9onbfh {
  stop-color: var(--svg-color--2b6f04, #2b6f04);
}

.r_xkoac5f {
  stop-color: var(--svg-color--66e604, #66e604);
}

.wjpmzabvz {
  stop-color: var(--svg-color--337c01, #337c01);
}

.x9hl5mork {
  stop-color: var(--svg-color--43c601, #43c601);
}

.z3isdab9b {
  d: path("M11.999 20.999a9 9 0 1 0 0-17.998a9 9 0 0 0 0 17.998M8.062 6.938l8.999 2.531l-1.406 7.874l-9-2.53z");
}

</style>
