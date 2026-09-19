<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4hxkmweh"/><circle class="xlagn2h0q"/><path class="mjqluf7zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:engie" /></template>
<style>
.j4hxkmweh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.042c7.243 0 13.9 1.115 19.167 2.98c.668.237 1.147-.651.585-1.084C39.3 17.508 32.12 15.276 24 15.276S8.7 17.508 4.248 20.938c-.562.433-.083 1.32.585 1.084c5.267-1.865 11.924-2.98 19.167-2.98");
}

.mjqluf7zf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.28 27.416v4.463m-20.203-1.403a2.78 2.78 0 0 1-2.415 1.403h0a2.78 2.78 0 0 1-2.78-2.78v-1.807a2.78 2.78 0 0 1 2.78-2.78h0a2.78 2.78 0 0 1 2.78 2.78v.903h-5.56m33.872 2.281a2.78 2.78 0 0 1-2.416 1.403h0a2.78 2.78 0 0 1-2.78-2.78v-1.807a2.78 2.78 0 0 1 2.78-2.78h0a2.78 2.78 0 0 1 2.78 2.78v.903h-5.56m-6.529-1.243a2.44 2.44 0 0 0-2.44-2.44h0a2.44 2.44 0 0 0-2.441 2.44v2.486a2.44 2.44 0 0 0 2.44 2.44h0a2.44 2.44 0 0 0 2.44-2.44h-2.44m-10.733 2.441v-7.367l4.88 7.367v-7.367");
}

.xlagn2h0q {
  cx: 32.28px;
  cy: 24.932px;
  r: 0.75px;
  fill: currentColor;
}

</style>
