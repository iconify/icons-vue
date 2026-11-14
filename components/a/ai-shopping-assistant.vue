<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kb9fjsbny"/><path class="j27eg9irw"/><path class="xm6jov88s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-shopping-assistant" /></template>
<style>
.j27eg9irw {
  fill: currentColor;
  d: path("M11.5 4.75q.9 3.85 5 4.75q-4.1.9-5 4.75q-.9-3.85-5-4.75q4.1-.9 5-4.75Z");
}

.kb9fjsbny {
  d: path("M11.881 16.5H11L7 20v-3.5h-.5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4 14V6q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T6.5 3.5h11q.123 0 .245.012t.243.036t.238.06t.231.082q.113.047.221.105q.109.058.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211q.058.108.105.221q.047.114.082.231t.06.238t.036.243T20 6v5.746");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xm6jov88s {
  d: path("M17 14.5h4.5v7H17L14.25 18Zm.5 3.5h.01");
}

</style>
