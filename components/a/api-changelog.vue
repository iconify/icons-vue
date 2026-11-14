<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trim47m6g"/><path class="phixk7bms"/><path class="wti3g3byz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-changelog" /></template>
<style>
.phixk7bms {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M8 11h.01m2.49 0h5.1M8 14.5h.01m2.49 0h.9m2.1 3a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.trim47m6g {
  d: path("M12.012 21.5H7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h6.5l6 6v2.515");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wti3g3byz {
  d: path("M17.5 15.5v2l1.5 1");
}

</style>
