<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c-t4vob-v"/><path class="o-zjk3bfx"/><path class="in7uxsbdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-seed-script" /></template>
<style>
.c-t4vob-v {
  d: path("M12.312 21.5H7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h6.5l6 6v2.515");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.in7uxsbdn {
  d: path("M15 15.25c0 .85 1.35 1.5 3 1.5s3-.65 3-1.5");
}

.o-zjk3bfx {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M9 10.5l-1.75 1.75L9 14m2.75-3.5l1.697 1.697m-.53.636L11.75 14M15 15.25c0-.85 1.35-1.5 3-1.5s3 .65 3 1.5v5c0 .85-1.35 1.5-3 1.5s-3-.65-3-1.5Z");
}

</style>
