<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4ye_5i4x"/><path class="vmkfn54mh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-report" /></template>
<style>
.h4ye_5i4x {
  d: path("M15.812 21.5H7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h6.5l6 6v3.615");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vmkfn54mh {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M7.5 17v-4.5m2.75 4.5V9.5M13 17v-5m5.491 3.048l-1.647 2.117a.672.672 0 0 0 .531 1.085a1.112 1.112 0 0 1 1.087 1.344l-.087.406a.385.385 0 0 0 .687.309l1.697-2.303A.632.632 0 0 0 20.25 17a1.072 1.072 0 0 1-1.06-1.235l.06-.39a.427.427 0 0 0-.759-.327");
}

</style>
