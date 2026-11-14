<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fkju8g9gf"/><path class="b-6pju0tt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:book-tour" /></template>
<style>
.b-6pju0tt {
  d: path("m19.25 14.25l2.25 2.25l-2.25 2.25");
}

.fkju8g9gf {
  d: path("M4 18.5V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T6.5 2.5H17v10.073M13.127 16H6.5q-.123 0-.245.012t-.243.036q-.12.024-.238.06t-.231.082t-.221.105t-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238t-.036.243T4 18.5t.012.245t.036.243t.06.238q.035.117.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036T6.5 21h5.719M7.5 6.5h5M15 22v-3a2.5 2.5 0 0 1 2.5-2.5h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
