<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="s_7cxcbce"/><path class="otjaj6iax"/><path class="jnyif3c4n"/><path class="hfr-pmy9f"/><path class="tz5f0oxst"/><path class="lrb4g1bwi"/><path clip-rule="evenodd" class="paazkgsfk"/><path clip-rule="evenodd" class="kvrtm44ln"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eth-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hfr-pmy9f {
  fill: var(--svg-color--74a0f3, #74a0f3);
  d: path("M12 20v-4.02l-5-2.9z");
}

.jnyif3c4n {
  fill: var(--svg-color--cba7f5, #cba7f5);
  d: path("M12 15.98V20l5-6.92z");
}

.kvrtm44ln {
  fill: var(--svg-color--202699, #202699);
  fill-rule: evenodd;
  d: path("m12 15.916l-5-2.84L12 20l5-6.924zm-4.44-2.34l4.36 2.48v3.56zm4.52 2.48v3.56l4.36-6.04z");
}

.lrb4g1bwi {
  fill: var(--svg-color--74a0f3, #74a0f3);
  d: path("m7 12.148l5 2.9V9.912z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.otjaj6iax {
  fill: var(--svg-color--cabcf8, #cabcf8);
  d: path("m12 4l-5 8.148l5-2.236z");
}

.paazkgsfk {
  fill: var(--svg-color--202699, #202699);
  fill-rule: evenodd;
  d: path("m12 15.048l-5-2.9L12 4l5 8.148zm-4.668-3.136l4.588-7.476v5.436zm-.068.204l4.656-2.068v4.768zm4.816-2.068v4.768l4.652-2.7zm0-.176l4.588 2.04l-4.588-7.476z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s_7cxcbce {
  fill: var(--svg-color--8ffcf3, #8ffcf3);
  d: path("M12 4v5.912l5 2.236z");
}

.tz5f0oxst {
  fill: var(--svg-color--cba7f5, #cba7f5);
  d: path("m12 15.048l5-2.9l-5-2.236z");
}

</style>
