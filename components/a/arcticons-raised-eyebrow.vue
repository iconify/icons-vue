<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="bfu1rrb0k"/><circle class="sruv5_b8f"/><circle class="u0gutabcx"/><circle class="e12nyyb1t"/><circle class="dbjv16wxy"/><circle class="raagn-npo"/><circle class="ro00ggbqz"/><path class="qaec5ebju"/></g><g class="y9tr6bcfx"><circle class="xz308nb_g"/><path class="s1jjbhtaf"/></g><path class="lu_qzc4qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arcticons-raised-eyebrow" /></template>
<style>
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

.lu_qzc4qa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.5 28.628h11m-11.855-9.615c1.072-.314 1.79-.406 2.755-.328c.967.078 1.647.39 2.565 1.337m8.676-1.362c-1.295-1.557-2.36-2.3-3.125-2.3c-1.12 0-1.577.35-2.14.902");
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

.s1jjbhtaf {
  d: path("M30.632 22.62c0-1.432-.681-2.593-2.195-2.593c-1.548 0-2.195 1.16-2.195 2.593s.647 2.852 2.195 2.852c1.585 0 2.194-1.42 2.194-2.852");
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

.xz308nb_g {
  cx: 20.106px;
  cy: 23.016px;
  r: 2.198px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
