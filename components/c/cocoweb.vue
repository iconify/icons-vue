<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h6eb1efou"/><path class="jr9z7kb0i"/><rect class="lrlc9-ihj"/><path class="m-0g0xb7o"/><rect class="aiq6jeb6p"/><path class="g3utmmb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cocoweb" /></template>
<style>
.aiq6jeb6p {
  width: 4.79px;
  height: 7.231px;
  x: 27.507px;
  y: 16.682px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.395px;
  ry: 2.395px;
}

.g3utmmb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.486 16.682l-.558 1.671");
}

.h6eb1efou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.5c11.042 0 17.918 5.076 19.5 5.5v18c-1.582.424-8.458 5.5-19.5 5.5S6.082 33.424 4.5 33V15c1.582-.424 8.458-5.5 19.5-5.5");
}

.jr9z7kb0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.482 26.125l-1.808 7.231l-1.807-7.231l-1.808 7.231l-1.808-7.231m9.162 3.615h2.357m1.258 3.616h-3.615v-7.231h3.615m4.913 3.615a1.808 1.808 0 1 1 0 3.616h-2.983v-7.231h2.983a1.808 1.808 0 1 1 0 3.615m0 0h-2.983m6.895-6.62c.443.578 1 .793 1.773.793h1.07c.996 0 1.804-.807 1.804-1.804v-.007c0-.997-.808-1.804-1.804-1.804h-1.18a1.806 1.806 0 0 1-1.806-1.806h0c0-1 .81-1.81 1.81-1.81h1.064c.773 0 1.33.215 1.773.793M12.29 21.488v.03a2.395 2.395 0 0 1-2.395 2.395h0A2.395 2.395 0 0 1 7.5 21.518v-2.44a2.395 2.395 0 0 1 2.395-2.396h0a2.395 2.395 0 0 1 2.395 2.395v.03");
}

.lrlc9-ihj {
  width: 4.79px;
  height: 7.231px;
  x: 14.169px;
  y: 16.682px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.395px;
  ry: 2.395px;
}

.m-0g0xb7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.629 21.488v.03a2.395 2.395 0 0 1-2.396 2.395h0a2.395 2.395 0 0 1-2.395-2.395v-2.44a2.395 2.395 0 0 1 2.395-2.396h0a2.395 2.395 0 0 1 2.395 2.395v.03");
}

</style>
