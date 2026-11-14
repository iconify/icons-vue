<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vu9b_xbqr"/><path class="ulvgu5pds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bag-charge" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ulvgu5pds {
  d: path("M15 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3-1.25v2.5");
}

.vu9b_xbqr {
  d: path("M13.042 21H7.5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T5 18.5v-15h3.5V6q0 .172.017.343t.05.34t.084.333t.115.323q.066.159.147.311t.177.294q.095.143.204.276q.11.133.231.255q.122.121.255.231q.133.109.276.204q.142.096.294.177t.311.147q.158.065.323.115t.333.084q.169.033.34.05T12 9.5t.343-.017t.34-.05t.333-.084t.323-.115q.159-.066.311-.147t.294-.177t.276-.204q.133-.11.255-.231q.121-.122.231-.255q.109-.133.204-.276q.096-.142.177-.294t.147-.311q.065-.158.115-.323t.084-.333t.05-.34T15.5 6V3.5H19v8.785");
}

</style>
