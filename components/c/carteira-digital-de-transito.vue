<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ewkcu_sro"/><rect transform="rotate(-74.304 29.99 24)" class="ln56i2brg"/><path class="ytcjr6byv"/><circle class="spjyh-bav"/><path class="k9xrvkb7j"/><rect class="rhz79_beu"/><path class="inwvjhv0m"/></g><circle class="kyet29clo"/><circle class="d9ht_edid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:carteira-digital-de-transito" /></template>
<style>
.d9ht_edid {
  cx: 19.441px;
  cy: 23.083px;
  r: 0.75px;
  fill: currentColor;
}

.ewkcu_sro {
  d: path("M18.691 31.238H5.494V14.514h17.897");
}

.inwvjhv0m {
  d: path("M18.691 25.084V26.6m10.508-1.516V26.6m-.561-5.518l-.719-2.153a1.51 1.51 0 0 0-1.43-1.03h-5.087c-.65 0-1.226.415-1.431 1.03l-.72 2.153");
}

.k9xrvkb7j {
  d: path("m13.229 21.777l.811.717a3.5 3.5 0 0 1 1.185 2.628v.525a.954.954 0 0 1-.953.953H8.689a.954.954 0 0 1-.954-.953v-.525a3.5 3.5 0 0 1 1.185-2.628l.812-.717");
}

.kyet29clo {
  cx: 28.449px;
  cy: 23.083px;
  r: 0.75px;
  fill: currentColor;
}

.ln56i2brg {
  width: 32.484px;
  height: 17.84px;
  x: 13.749px;
  y: 15.08px;
  rx: 2px;
  ry: 2px;
}

.rhz79_beu {
  width: 12.789px;
  height: 4.002px;
  x: 17.55px;
  y: 21.082px;
  rx: 0.6px;
  ry: 0.6px;
}

.spjyh-bav {
  cx: 11.48px;
  cy: 20.233px;
  r: 2.334px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ytcjr6byv {
  d: path("m35.314 38.031l-17.175-4.826");
}

</style>
