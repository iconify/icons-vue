<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="itfaf6d7d"/><rect class="gw3pv5fcu"/><path class="yo9zh7bbx"/><circle class="p5l0i8bez"/><circle class="kfom7cc5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-kadence" /></template>
<style>
.gw3pv5fcu {
  width: 20px;
  height: 20px;
  x: 11px;
  y: 11px;
  fill: var(--svg-color--0e6e6e, #0e6e6e);
  rx: 4.4px;
}

.itfaf6d7d {
  fill: var(--svg-color--16a39b, #16a39b);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.kfom7cc5r {
  cx: 25.75px;
  cy: 23.25px;
  r: 1.5px;
  fill: var(--svg-color--fff, #fff);
}

.p5l0i8bez {
  cx: 25.75px;
  cy: 18.75px;
  r: 1.5px;
  fill: var(--svg-color--fff, #fff);
}

.yo9zh7bbx {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.5 15h4v12h-4zm6 0h1.75v12H20.5z");
}

</style>
