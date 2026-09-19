<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oplog9ewq"/><path class="n95nv995l"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fixprice" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n95nv995l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.203 11.624a.555.555 0 0 0-.556.554v23.643c0 .308.248.556.556.556h5.563a.555.555 0 0 0 .556-.554v-9.068h1.712a.555.555 0 0 0 .557-.553V21.56a.555.555 0 0 0-.553-.557h-1.715v-3.628h1.712a.555.555 0 0 0 .556-.554v-4.642a.555.555 0 0 0-.554-.556h-5.803z");
}

.oplog9ewq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.147 21.004h7.767c.308 0 .556.248.556.556v4.639a.555.555 0 0 1-.554.556h-7.769a.555.555 0 0 1-.556-.554V21.56c0-.308.248-.556.556-.556m0-9.38h8.649c.309 0 .557.249.557.556v4.64a.555.555 0 0 1-.555.555h-8.65a.555.555 0 0 1-.557-.553v-4.641c0-.307.248-.555.556-.555z");
}

</style>
