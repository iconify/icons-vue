<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cq-c99b6s"/><ellipse class="yl_il6bfg"/><path class="yrn-m0bnb"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:b612" /></template>
<style>
.cq-c99b6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.754 24c1.423 0 2.577 1.137 2.577 2.539s-1.154 2.539-2.577 2.539H9.5V18.923h4.254c1.423 0 2.577 1.137 2.577 2.539S15.177 24 13.754 24m-.004.004H9.5");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.yl_il6bfg {
  cx: 21.778px;
  cy: 25.714px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.416px;
  ry: 3.364px;
}

.yrn-m0bnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.891 20.162c-.569-.734-1.436-1.238-2.873-1.238h-.24c-1.887 0-3.416 1.506-3.416 3.363v3.428m8.508-5.407l2.766-1.381v10.15m2.034-6.791c0-2.076 1.909-3.713 4.092-3.3c1.433.272 2.576 1.492 2.72 2.921c.105 1.064-.236 2.113-.982 2.758c-1.382 1.194-5.83 4.413-5.83 4.413h6.83");
}

</style>
