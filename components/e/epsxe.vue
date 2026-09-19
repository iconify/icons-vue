<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="n9t53rbiv"/><circle class="wzfx5xb2m"/><circle class="nqzag0b4r"/><circle class="h9g9ksb1c"/><path class="fg7bk3gou"/><path class="h2jxq0bhn"/><path class="sjzf-92wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:epsxe" /></template>
<style>
.fg7bk3gou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.708 24.118v-1.296l-1.296-1.297l-1.297 1.297v1.296zm0-7.78v1.297l-1.296 1.297l-1.297-1.297v-1.297zm2.594 2.594h-1.297l-1.297 1.296l1.297 1.297h1.297zm-7.78 0h1.297l1.296 1.296l-1.296 1.297H8.522zm30.955-3.959l-.44-2.403c-.23-1.256-2.252-1.496-3.529-1.493c-1.17.004-2.963.358-3.172 1.51l-.41 2.27");
}

.h2jxq0bhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.774 20.61a6.856 6.856 0 0 1 6.835-6.835c2.858.003 5.444 1.78 6.37 4.483c.147.426.235.884.28 1.361l1.219 12.684c.438 4.566-5.71 6.438-7.89 2.4l-6.057-11.216c-.493-.912-.758-1.863-.758-2.876zM8.522 14.973l.44-2.403c.23-1.256 2.252-1.496 3.529-1.493c1.17.004 2.963.358 3.172 1.51l.41 2.27m.859 11.471h14.135m-14.31-10.977h14.497");
}

.h9g9ksb1c {
  cx: 39.03px;
  cy: 20.344px;
  r: 1.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n9t53rbiv {
  cx: 35.702px;
  cy: 23.672px;
  r: 1.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nqzag0b4r {
  cx: 32.373px;
  cy: 20.344px;
  r: 1.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sjzf-92wv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.226 20.609a6.856 6.856 0 0 0-6.835-6.836c-2.858.004-5.445 1.78-6.37 4.483a6 6 0 0 0-.28 1.36L4.521 32.3c-.438 4.567 5.71 6.439 7.89 2.401l6.057-11.216c.493-.912.758-1.863.758-2.876");
}

.wzfx5xb2m {
  cx: 35.702px;
  cy: 17.015px;
  r: 1.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
