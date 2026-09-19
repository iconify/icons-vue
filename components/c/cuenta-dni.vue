<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="osnyqj36v"/><path class="qgwpy5rnh"/></g><path class="ysypcbxkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cuenta-dni" /></template>
<style>
.osnyqj36v {
  d: path("M34.378 14.327s-3.772.09-5.068 2.333c-1.193 2.064-.966 3.62-.966 3.62s.028 6.858.08 9.654c.054 2.796-.643 4.023-2.09 4.023h-4.828");
}

.qgwpy5rnh {
  d: path("M37.194 19.999h-5.632s.161-2.816 2.816-2.816s2.816 2.816 2.816 2.816m-26.388-2.615s1.77-3.781 6.356-3.298m2.252 5.792h-5.631s.16-2.816 2.815-2.816s2.816 2.816 2.816 2.816");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ysypcbxkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.457v-6a4 4 0 0 1 4-4h6m27 27v6a4 4 0 0 1-4 4h-6m0-37h6a4 4 0 0 1 4 4v6m-37 17.558a9 9 0 0 0 1.05 2.802c.49.844 1.115 1.604 1.787 2.312c.935.984 1.975 1.88 3.152 2.557c1.222.701 2.576 1.156 3.958 1.435c1.38.28 2.796.385 4.203.316");
}

</style>
