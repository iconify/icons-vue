<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="bfu1rrb0k"/><circle class="sruv5_b8f"/><circle class="u0gutabcx"/><circle class="e12nyyb1t"/><circle class="dbjv16wxy"/><circle class="raagn-npo"/><circle class="ro00ggbqz"/><path class="qaec5ebju"/></g><path class="y_3g3lbki"/><path class="y1dz4vwkp"/><path class="aeeairdes"/><path class="z0g7ijqxt"/><path class="xk--qzvli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arcticons-pleading" /></template>
<style>
.aeeairdes {
  fill: currentColor;
  d: path("M18.712 18.627a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m8.123 0a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

.bfu1rrb0k {
  d: path("m24 10.84l-11.4 6.58v13.16L24 37.16l11.4-6.58V17.42z");
}

.dbjv16wxy {
  cx: 39.93px;
  cy: 33.2px;
  r: 3.11px;
}

.e12nyyb1t {
  cx: 39.93px;
  cy: 14.8px;
  r: 3.11px;
}

.qaec5ebju {
  d: path("m12.6 30.58l-1.84 1.06M24 37.16v2.12m0-28.44V8.71m11.4 21.87l1.84 1.06M35.4 17.42l1.84-1.06M12.6 17.42l-1.84-1.06");
}

.raagn-npo {
  cx: 24px;
  cy: 42.39px;
  r: 3.11px;
}

.ro00ggbqz {
  cx: 8.07px;
  cy: 33.2px;
  r: 3.11px;
}

.sruv5_b8f {
  cx: 8.07px;
  cy: 14.8px;
  r: 3.11px;
}

.u0gutabcx {
  cx: 24px;
  cy: 5.61px;
  r: 3.11px;
}

.xk--qzvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.085 20.175a6.01 6.01 0 0 1-5.217 3.024a6 6 0 0 1-1.974-.332");
}

.y_3g3lbki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.504 29.331c.744-.234 1.527-.338 2.496-.338s1.753.104 2.497.338m-3.363-7.061c0-2.417-.12-5.118-2.447-5.118c-4.004 0-5.687 4.322-5.687 5.895c0 1.925 1.773 2.856 4.19 2.856s3.944-.936 3.944-3.633");
}

.y1dz4vwkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.915 20.175a6.01 6.01 0 0 0 5.217 3.024a6 6 0 0 0 1.974-.332");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z0g7ijqxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.866 22.27c0-2.417.12-5.118 2.447-5.118c4.004 0 5.687 4.322 5.687 5.895c0 1.925-1.773 2.856-4.19 2.856s-3.944-.936-3.944-3.633");
}

</style>
