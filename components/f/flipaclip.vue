<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n7jt0ybih"/><path class="kqj78_b_g"/><path class="zr5fy4vqb"/><path class="a2kq2ebuu"/><path class="r11o3hfyu"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flipaclip" /></template>
<style>
.a2kq2ebuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.561 23.194c.084-2.372-1.99-3.03-3.56-3.03c-2.062 0-3.604 1.85-3.604 4.009s2.651 3.378 3.688 3.378");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.kqj78_b_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 20.458c0 2.72-7.891 5.53-13.155 7.192a2.61 2.61 0 0 0-1.809 2.26C27.001 35.804 25.586 42.5 21 42.5");
}

.n7jt0ybih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 16.252c0 3.11-6.527 6.218-15.673 7.011a2.996 2.996 0 0 0-2.752 3.029c.128 8.602-.89 16.208-9.327 16.208m22.065-8.248v3.645m1.823-1.822h-3.645");
}

.r11o3hfyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.983 20.322s-.988-4.041-1.87-5.57c-2.398 1.346-4.865 6.757-4.865 6.757c.659.21 4.752.436 4.752.436m1.462 5.106c-.845.795-2.847 4.51-2.847 4.51c1.203 1.051 4.224 1.063 4.224 1.063m2.968-11.51c1.23-1.581 2.885-3.474 2.885-3.474c1.822 1.514 2.936 4.747 2.936 4.747");
}

.zr5fy4vqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.537 21.603c-.308-5.042-7.542-9.374-13.177-9.374s-9.967 5.257-9.967 12.785s5.972 10.22 9.588 10.22c.645 0 1.444-.123 1.444-.123");
}

</style>
