<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGPmCkdbYV)" class="g_hj7v3tk"/><defs><linearGradient id="SVGPmCkdbYV" x1="6.429" x2="19.136" y1="3.964" y2="22.163" gradientUnits="userSpaceOnUse"><stop class="qepogybki"/><stop offset="1" class="u28bw3nsy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apl" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g_hj7v3tk {
  d: path("M9.015 3.017c-.154.016-.23.055-.266.133c-.053.113-.01.21.896 2.039c.237.476.444.92.46.983a.9.9 0 0 1-.002.467c-.016.066-.208.482-.425.923c-.545 1.107-.805 1.643-2.992 6.16l-2.618 5.403c-.433.892-.71 1.483-.724 1.55c-.029.136 0 .21.107.272c.07.04.106.043 1.222.049c1.353.007 1.602-.007 1.78-.09c.242-.111.29-.185.679-.984l.905-1.858c.306-.627 1.088-2.24 1.738-3.583c1.337-2.761 2.129-4.385 2.153-4.41c.063-.062.605 1.039 4.64 9.404c.306.634.591 1.198.632 1.254a.7.7 0 0 0 .155.156c.165.115.167.115 1.547.115c1.131 0 1.298-.004 1.515-.04q.125-.015.25-.044a3 3 0 0 0-.112-.308c-.13-.327-.235-.544-3.322-6.897q-2.13-4.37-4.244-8.746c-.806-1.674-.788-1.636-.936-1.774C11.84 2.994 11.886 3 10.415 3c-.692 0-1.323.008-1.4.017");
}

.qepogybki {
  stop-color: var(--svg-color--5e9ff9, #5e9ff9);
}

.u28bw3nsy {
  stop-color: var(--svg-color--0050f9, #0050f9);
}

</style>
