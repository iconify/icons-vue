<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="grazetbaf"/><path class="r1pdqwb1p"/><path class="jnyif3c4n"/><path class="hfr-pmy9f"/><path class="mt5sl2bgs"/><path class="sc8ei0bgo"/><path clip-rule="evenodd" class="wwc13zb9t"/><path clip-rule="evenodd" class="wszbl4hyk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ethereum-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.grazetbaf {
  fill: var(--svg-color--8ffcf3, #8ffcf3);
  d: path("M12 4v5.912l5 2.237z");
}

.hfr-pmy9f {
  fill: var(--svg-color--74a0f3, #74a0f3);
  d: path("M12 20v-4.02l-5-2.9z");
}

.jnyif3c4n {
  fill: var(--svg-color--cba7f5, #cba7f5);
  d: path("M12 15.98V20l5-6.92z");
}

.mt5sl2bgs {
  fill: var(--svg-color--cba7f5, #cba7f5);
  d: path("m12 15.049l5-2.9l-5-2.236z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r1pdqwb1p {
  fill: var(--svg-color--cabcf8, #cabcf8);
  d: path("m12 4l-5 8.148l5-2.235z");
}

.sc8ei0bgo {
  fill: var(--svg-color--74a0f3, #74a0f3);
  d: path("m7 12.149l5 2.9V9.913z");
}

.wszbl4hyk {
  fill: var(--svg-color--202699, #202699);
  fill-rule: evenodd;
  d: path("m12 15.917l-5-2.84L12 20l5-6.924zm-4.44-2.341l4.36 2.48v3.56zm4.519 2.48v3.56l4.36-6.04z");
}

.wwc13zb9t {
  fill: var(--svg-color--202699, #202699);
  fill-rule: evenodd;
  d: path("m12 15.048l-5-2.9L12 4l5 8.148zm-4.67-3.136l4.588-7.475v5.435zm-.068.204l4.656-2.068v4.768zm4.816-2.068v4.768l4.653-2.7zm0-.176l4.588 2.04l-4.588-7.475z");
}

</style>
