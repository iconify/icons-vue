<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qjali6bpr"/><path class="df7t8_bfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:build-config" /></template>
<style>
.df7t8_bfv {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-2.684 5.823l.085-1.283h1.198l.085 1.283l1.079.447l.967-.847l.847.847l-.847.967l.447 1.079l1.283.085v1.198l-1.283.085l-.447 1.079l.847.967l-.847.847l-.967-.847l-1.079.447l-.085 1.283h-1.198l-.085-1.283l-1.079-.447l-.967.847l-.847-.847l.847-.967l-.447-1.079l-1.283-.085v-1.198l1.283-.085l.447-1.079l-.847-.967l.847-.847l.967.847Z");
}

.qjali6bpr {
  d: path("M11.212 21.5H7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h6.5l6 6v1.715");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
