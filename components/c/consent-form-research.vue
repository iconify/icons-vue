<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xpvd3lb1g"/><path class="azq4zwbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:consent-form-research" /></template>
<style>
.azq4zwbaf {
  d: path("M12.5 2.5v4a2 2 0 0 0 2 2h4M7 12h6m-6 5h4m9.311-3.689l.378.378a1.5 1.5 0 0 1 0 2.122L16.34 20.16a1.5 1.5 0 0 1-.814.419l-1.026.171a.96.96 0 0 1-1.082-1.212l.475-1.664a1.5 1.5 0 0 1 .382-.649l3.914-3.914a1.5 1.5 0 0 1 2.122 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpvd3lb1g {
  d: path("M11.012 21.5H6q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T3.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T6 2.5h6.5l6 6v1.615");
}

</style>
