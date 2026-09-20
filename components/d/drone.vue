<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-69.071 32.654 35.807)" class="elh6hl01g"/><path class="k6xanybqu"/><circle class="j6218ab0v"/><path class="lpuwmmfxr"/><ellipse transform="rotate(-20.929 15.346 35.807)" class="tt304bhmz"/><path class="cbbqdmdec"/><path class="rao-s51ix"/><path class="mlsssabum"/><circle class="oxxga6lua"/><path class="bhrqmlb8l"/><ellipse class="opuj1fb6v"/><path class="pixyr8e3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drone" /></template>
<style>
.bhrqmlb8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.537 19.512c.334-1.071.964-1.777 1.625-2.31c.582.097 1.074.421 1.235.859c-.226.664-.924 2.034-1.424 2.656m.921-3.242l.457-.707m1.365.022l-.816.3l-1.12-.657l-.07-1.094C11.336 11.8 14.382 6.514 24 6.514s12.665 5.287 14.29 8.825l-.07 1.094l-1.12.656l-.815-.3m-27.06 5.547c.262-.36.556-.683.868-.893c.446-.3.929-.373 1.407-.004");
}

.cbbqdmdec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.779 41.77a12.8 12.8 0 0 0 4.329-2.83m-16.216 0q0 0 0 0a12.8 12.8 0 0 0 4.329 2.83m14.228-5.972q.47-.858.85-1.802c1.052-2.622 1.569-5.725 1.569-9.169c0-1.186-.125-2.32-.368-3.388c-1.02-4.486-4.112-7.81-8.727-8.945c-1.132-.28-2.394-.426-3.773-.426s-2.64.146-3.773.426c-4.615 1.135-7.708 4.459-8.727 8.945a15.3 15.3 0 0 0-.368 3.388c0 3.444.517 6.547 1.569 9.17q.38.943.85 1.801M8.908 21.445a.334.334 0 0 1 .317.333v13.177c0 .185-.15.334-.335.334H6.21a.335.335 0 0 1-.335-.335V21.779c0-.178.14-.325.317-.333m-.318.953h-.636c-1.61 1.191-2.694 3.417-2.694 5.967s1.084 4.777 2.693 5.968h.637");
}

.elh6hl01g {
  cx: 32.654px;
  cy: 35.807px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.341px;
  ry: 1.706px;
}

.j6218ab0v {
  cx: 40.451px;
  cy: 20.956px;
  r: 1.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k6xanybqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.809 21.445a.334.334 0 0 1 .317.333v13.177c0 .185-.15.334-.335.334H39.11a.335.335 0 0 1-.335-.335V21.779c0-.178.14-.325.317-.333m3.034.953h.636c1.61 1.191 2.694 3.417 2.694 5.967s-1.084 4.777-2.693 5.968h-.637m-9.75-23.051c-.183 1.037-.203 2.167-.18 3.282m-4.423-2.071s1.873-.706 2.86-2.363m-.247-2.621C32.76 4.904 34.95 3.763 38.1 3.03a1.133 1.133 0 0 1 1.388 1.07c.084 2.616-.316 5.995-1.93 9.759");
}

.lpuwmmfxr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.027 20.717c-.5-.622-1.198-1.992-1.424-2.656c.16-.438.652-.762 1.235-.86c.66.534 1.291 1.24 1.625 2.311m-2.357-2.037l-.457-.707m1.126 17.926c-.866.683-2.304.674-2.922.243l-.034-.025a1.5 1.5 0 0 1-.52-.916m-26.074.698c.866.683 2.304.674 2.922.243l.034-.025c.224-.172.463-.53.52-.916M36.5 21.439c.478-.369.961-.296 1.407.004c.312.21.606.533.868.893M24 36.889a4.82 4.82 0 1 1 0-9.64a4.82 4.82 0 0 1 0 9.64");
}

.mlsssabum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.006 21.19C36.307 8.885 27.27 8.885 24 8.885s-12.307 0-13.006 12.303");
}

.opuj1fb6v {
  cx: 24px;
  cy: 42.892px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.779px;
  ry: 2.108px;
}

.oxxga6lua {
  cx: 7.549px;
  cy: 20.956px;
  r: 1.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pixyr8e3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.22 42.892v-1.994c0-1.164 1.693-2.108 3.78-2.108s3.78.944 3.78 2.108v1.994");
}

.rao-s51ix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.805 14.565c.022-1.115.002-2.245-.181-3.282m1.743-1.153c.987 1.658 2.86 2.364 2.86 2.364M17.614 7.51C15.24 4.904 13.05 3.763 9.9 3.03A1.133 1.133 0 0 0 8.512 4.1c-.084 2.616.315 5.995 1.93 9.759");
}

.tt304bhmz {
  cx: 15.346px;
  cy: 35.807px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.706px;
  ry: 3.341px;
}

</style>
