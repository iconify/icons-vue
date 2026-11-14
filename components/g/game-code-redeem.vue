<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mozy2sqvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-code-redeem" /></template>
<style>
.mozy2sqvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.354 16.5H3V13q.123 0 .245-.012t.243-.036t.238-.06q.117-.035.231-.082q.113-.047.221-.105q.109-.058.211-.126q.102-.069.197-.146q.095-.078.182-.165t.165-.182t.146-.197t.126-.211t.105-.221q.047-.114.082-.231t.06-.238t.036-.243t.012-.245t-.012-.245t-.036-.243q-.024-.12-.06-.238t-.082-.231t-.105-.221t-.126-.211q-.069-.102-.146-.197q-.078-.095-.165-.182t-.182-.165t-.197-.146t-.211-.126q-.108-.058-.221-.105q-.114-.047-.231-.082t-.238-.06q-.121-.024-.243-.036T3 8V4.5h18V8q-.123 0-.245.012t-.243.036t-.238.06q-.117.035-.231.082q-.113.047-.221.105q-.109.058-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238t-.036.243t-.012.245q0 .181.026.359q.026.179.077.352t.127.337t.174.315t.218.287t.257.253t.29.213t.318.169M7.75 8.5H14m-6.25 4H11m3.75 5.5l2 2L21 15.75");
}

</style>
