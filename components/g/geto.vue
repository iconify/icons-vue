<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bo-6610xi"/><circle class="smh8hwt4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geto" /></template>
<style>
.bo-6610xi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.042 35.9l-1.327-2.3a4 4 0 0 1 1.033-5.176l.243-.186c1.773-1.357 2.612-2.431 2.612-4.237s-1.042-3.038-2.612-4.24l-.243-.186A4 4 0 0 1 4.716 14.4l1.327-2.3a4 4 0 0 1 4.999-1.694l.283.117c2.062.857 3.412 1.047 4.976.144c1.563-.903 2.11-2.421 2.365-4.382l.04-.303a4 4 0 0 1 3.968-3.483h2.654a4 4 0 0 1 3.967 3.482l.04.304c.289 2.214.8 3.478 2.363 4.381c1.564.903 3.152.616 4.978-.142l.282-.118a4 4 0 0 1 5 1.694l1.327 2.3a4 4 0 0 1-1.033 5.176l-.243.186c-1.773 1.357-2.612 2.431-2.612 4.237s1.042 3.038 2.612 4.24l.242.186a4 4 0 0 1 1.032 5.177L41.956 35.9a4 4 0 0 1-5 1.694l-.282-.117c-2.062-.857-3.412-1.047-4.976-.144s-2.11 2.421-2.366 4.382l-.04.304a4 4 0 0 1-3.966 3.482h-2.654a4 4 0 0 1-3.967-3.482l-.04-.304c-.289-2.214-.8-3.478-2.363-4.381s-3.152-.616-4.978.142l-.283.118A4 4 0 0 1 6.042 35.9");
}

.smh8hwt4g {
  cx: 24px;
  cy: 24px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
