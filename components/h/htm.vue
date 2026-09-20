<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG0EMTbUhQ)" class="q4vo8r5ql"/><defs><linearGradient id="SVG0EMTbUhQ" x1="12" x2="12" y1="3.3" y2="20.7" gradientUnits="userSpaceOnUse"><stop class="ufqgwyb2e"/><stop offset="1" class="h1e19bxct"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:htm" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h1e19bxct {
  stop-color: var(--svg-color--33cbf0, #33cbf0);
}

.q4vo8r5ql {
  d: path("M5.388 7.53c-1.14-1.302-.69-3.36-.318-4.23C4.488 3.516 3 4.656 3 7.53c0 3.252 3.66 4.716 5.256 6.504s2.07 6.666 3.66 6.666c1.596 0 2.328-5.328 3.828-6.666C17.016 12.894 21 10.614 21 7.53c0-2.472-1.38-3.852-2.07-4.23c1.146 1.692.318 3.252-.636 4.23c-3.186 3.576-5.736 2.28-6.372 5.364c-.318-3.09-5.1-3.738-6.534-5.364");
}

.ufqgwyb2e {
  stop-color: var(--svg-color--64eab7, #64eab7);
}

</style>
