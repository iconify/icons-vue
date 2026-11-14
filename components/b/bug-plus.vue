<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il5lg2bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bug-plus" /></template>
<style>
.il5lg2bqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.221 15.813q-.172.164-.373.292q-.2.129-.421.217t-.455.133t-.472.045h-4q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4 14V8q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06t.243-.036T6.5 5.5h4q.123 0 .245.012t.243.036q.12.024.238.06t.231.082t.221.105t.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211q.058.108.105.221q.047.114.082.231t.06.238q.024.121.036.243T13 8v6q0 .32-.081.631q-.081.31-.237.589M6 5.5a2.5 2.5 0 0 1 5 0m-2.5 0v11M4 8.5L2 7m2 4.5H2m2 3L2 15m11-6.5L15 7m-2 4.5h2m-2 3l2 .5m3 0v6m-3-3h6");
}

</style>
