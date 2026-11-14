<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmobegx4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bug-critical" /></template>
<style>
.qmobegx4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.82 16.862Q12.422 17 12 17H8q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T5.5 14.5v-6q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221t.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06t.243-.036T8 6h4q.123 0 .245.012t.243.036q.12.024.238.06t.231.082t.221.105t.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211q.058.108.105.221q.047.114.082.231t.06.238q.024.121.036.243t.012.245v5.173M8 6a2 2 0 0 1 4 0M5.5 9.5L3 8.5m2.5 5l-2.5 1m11.5-5l2.5-1m.75 5l4.25 8h-8.5Zm0 3V18m0 1.75h.01");
}

</style>
