<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="lmqoe6bel"/><path class="ww604zb1w"/><path class="v-rlbifku"/><path class="os-x9p34q"/><path class="n8yb0wb1h"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:loc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lmqoe6bel {
  fill: var(--svg-color--b6b6b6, #b6b6b6);
  d: path("M13.364 10.339c.824 0 1.318.635 1.459.955h-.659a.99.99 0 0 0-.804-.39c-.956.042-1.125.898-1.069 1.322a4 4 0 0 1-.503-.734c.047-.188.536-1.153 1.572-1.153z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.n8yb0wb1h {
  fill: var(--svg-color--2d7cf2, #2d7cf2);
  d: path("M4.47 11.972c0-5.242 4.937-7.082 7.059-7.03v1.411c-1.943-.028-5.647 1.93-5.647 5.62c0 4.45 3.882 5.656 5.647 5.674v1.412c-2.555.01-7.059-1.976-7.059-7.087");
}

.os-x9p34q {
  fill: var(--svg-color--243a45, #243a45);
  d: path("M19.53 12c-.301 6.376-5.435 7.99-8 8v-2.353c4.41-.15 5.619-3.882 5.647-5.647z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v-rlbifku {
  fill: var(--svg-color--a2c5bf, #a2c5bf);
  d: path("M19.53 12c-.301-6.376-5.435-7.99-8-8v2.353c4.41.15 5.619 3.882 5.647 5.647z");
}

.ww604zb1w {
  fill: var(--svg-color--b6b6b6, #b6b6b6);
  d: path("M13.411 13.091c.466 0 .706-.282.767-.41h.645c-.146.424-.748.918-1.365.975c-.37.03-.74-.067-1.049-.273c-.497-.38-.9-.87-1.177-1.43c-.437-.824-.94-1.06-1.336-1.06c-.762 0-1.143.688-1.106 1.06c0 .908.753 1.138 1.177 1.138c.828-.052 1.035-.908.978-1.237l.448.715a1.65 1.65 0 0 1-1.497 1.082c-.616-.005-1.661-.475-1.661-1.699c0-1.002.847-1.604 1.661-1.604c.87 0 1.478.659 1.765 1.233c.23.46.635.927.81 1.1c.117.147.47.41.94.41");
}

</style>
