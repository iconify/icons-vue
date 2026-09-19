<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="mu9l94_fh"/><path class="zz6xzubgp"/><path class="rgybmxbek"/><path class="mj48htb0l"/></g><path class="i6h3e7baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:go-mobile" /></template>
<style>
.i6h3e7baw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.925 24.118l4.019 6.96m8.037 0h-8.037m-4.019 6.961l4.019-6.961m8.037 0L24 38.039m8.038 0H24M19.981 45L24 38.039m8.262-13.921l4.019 6.96m8.037 0h-8.037m-4.019 6.961l4.019-6.961M32.038 9.961l4.018 6.961m8.038 0h-8.038m-4.018 6.96l4.018-6.96M19.981 3L24 9.961m8.038 0H24m-4.019 6.961L24 9.961m-16.075 0l4.019 6.961m8.037 0h-8.037m-4.019 6.96l4.019-6.96");
}

.mj48htb0l {
  d: path("M7.925 23.882h8.037l4.019-6.96l-4.019-6.961H7.925l-4.019 6.961zm0 14.157h8.037l4.019-6.961l-4.019-6.96H7.925l-4.019 6.96z");
}

.mu9l94_fh {
  d: path("M19.981 45h8.038l4.019-6.961l-4.019-6.961h-8.038l-4.019 6.961z");
}

.rgybmxbek {
  d: path("M19.981 16.922h8.038l4.019-6.961L28.019 3h-8.038l-4.019 6.961z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zz6xzubgp {
  d: path("M32.038 38.039h8.037l4.019-6.961l-4.019-6.96h-8.037l-4.019 6.96zm0-14.157h8.037l4.019-6.96l-4.019-6.961h-8.037l-4.019 6.961z");
}

</style>
