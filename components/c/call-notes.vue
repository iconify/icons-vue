<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oek1v8b1m"/><path class="nfnqujd9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-notes" /></template>
<style>
.nfnqujd9u {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M8 7.5h2.5m-2.5 4h8m-8 4h4m4.25-1h1.25l.75 1.75l-1 .75q.75 1.5 2.25 2.25l.75-1L22 19v1.25a1 1 0 0 1-1 1c-3.25-.25-5.75-2.75-6-5.75a1 1 0 0 1 1.25-1Z");
}

.oek1v8b1m {
  d: path("M15.012 21.5H7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h6.5l6 6v3.615");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
