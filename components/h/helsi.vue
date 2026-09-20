<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="pp5u1eb3j"/><path class="zibioc04d"/></g><circle class="fo36lwdsk"/><path class="qx68--rxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:helsi" /></template>
<style>
.fo36lwdsk {
  cx: 34.053px;
  cy: 25.077px;
  r: 0.75px;
  fill: currentColor;
}

.pp5u1eb3j {
  d: path("M27.755 16.21C25.332 9.914 13.22 9.914 13.22 20.572c-11.628 0-11.628 15.503 0 15.503h9.689m2.907-13.08c2.907-7.268 11.143-4.36 11.143 1.937c8.72 0 8.72 11.143 0 11.143H25.332M12.736 24.64v7.752");
}

.qx68--rxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.053 27.45v5.136");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zibioc04d {
  d: path("M12.736 29.534a1.938 1.938 0 1 1 3.876 0v3.197m6.044-1.026a1.938 1.938 0 0 1-3.622-.96v-1.26a1.938 1.938 0 1 1 3.876 0v.63h-3.876m6.298-5.184v6.783a.97.97 0 0 0 .97.969h.29m1.56-.433c.354.297.735.433 1.594.433h.435c.707 0 1.28-.575 1.28-1.284s-.573-1.284-1.28-1.284h-.87c-.707 0-1.28-.575-1.28-1.284s.574-1.284 1.28-1.284h.436c.857 0 1.24.137 1.594.433");
}

</style>
