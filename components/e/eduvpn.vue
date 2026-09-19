<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bkie-iv2c"/><path class="i4k7oobuu"/><path class="g97dv0b2u"/><path class="u2d0ufbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eduvpn" /></template>
<style>
.bkie-iv2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.632L4.5 10.054l8.987 2.716l-.05 4.095m-.036 2.515l-.13 12.508A19.75 19.75 0 0 0 24 42.368M8.77 17.285v-5.871");
}

.g97dv0b2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 5.632l19.5 4.422l-8.987 2.717l.05 4.095m.036 2.515l.13 12.508A19.75 19.75 0 0 1 24 42.369");
}

.i4k7oobuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.59 17.632c5.994-2.973 10.194.24 11.41 1.548c-1.409 3.493-9.128 3.875-11.41-1.548m12.18 6.188v14.908c3.157-1.642 6.654-4.91 7.132-7.556v-7.076c-1.166.28-2.337 1.163-7.133-.276Z");
}

.u2d0ufbxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.41 17.632c-5.994-2.973-10.195.24-11.41 1.549c1.408 3.492 9.128 3.874 11.41-1.549");
}

</style>
