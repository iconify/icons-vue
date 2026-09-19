<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="lmzq0_b9m"/><circle class="almj2064m"/><path class="fgmzy1bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calces" /></template>
<style>
.almj2064m {
  cx: 24px;
  cy: 31.077px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fgmzy1bhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.855 36.907h5v3h-5zm9.097 0h5v2.999h-5zm9.096 0h5v3h-5zm9.097 0h5v3h-5zM9.75 21.67c0 .516.587.892 1.292.892c.67 0 1.094-.72 1.246-2.48l.224-2.674c.106-1.3.529-4.327.67-4.918c.2-.816.658-1.858 1.775-1.858c.705 0 1.293.376 1.293.892c0 .322-.195.675-.43.675m21.381 4.374l-3.099 4.106m3.099 0l-3.099-4.106m-9.072 0l-3.099 4.106m3.099 0l-3.099-4.106m-1.014-1.875s-1.55 1.761-1.55 3.932s1.55 3.932 1.55 3.932m5.128-7.864s1.55 1.761 1.55 3.932s-1.55 3.932-1.55 3.932m6.225-4.44a1.55 1.55 0 0 0-1.55-1.55h0a1.55 1.55 0 0 0-1.549 1.55v1.008c0 .855.694 1.55 1.55 1.55h0a1.55 1.55 0 0 0 1.55-1.55m-.001 1.549v-6.198M16.23 20.68v-5.114c0-.6.485-1.085 1.084-1.085h0c.534 0 .867.158 1.096.454m-3.099 1.638h2.169");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.lmzq0_b9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.855 8.5h32.29v16.194H7.855zm0 20.645h7.73v3.865h-7.73zm24.56 0h7.73v3.865h-7.73z");
}

</style>
