<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z8w7hpboy"/><path class="fwee8n8_c"/><path class="u-t_5ekod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deduplication" /></template>
<style>
.fwee8n8_c {
  d: path("M18.549 21.269q-.499.231-1.049.231h-7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T8 19V9q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126t.221-.105q.114-.047.231-.082t.238-.06t.243-.036t.245-.012h5L20 11v4.736");
}

.u-t_5ekod {
  d: path("M15.5 6.5V9a2 2 0 0 0 2 2H20m-4.5 7.5h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8w7hpboy {
  d: path("M8 18H6a2 2 0 0 1-2-2V4.5a2 2 0 0 1 2-2h7.5a2 2 0 0 1 2 2v2");
}

</style>
