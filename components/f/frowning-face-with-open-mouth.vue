<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="vrd83_b4t"/><ellipse class="j_ykwbb4m"/><path class="fu1pm9bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:frowning-face-with-open-mouth" /></template>
<style>
.fu1pm9bay {
  fill: var(--svg-color--664500, #664500);
  d: path("M23.485 27.879C23.474 27.835 22.34 23.5 18 23.5s-5.474 4.335-5.485 4.379a.5.5 0 0 0 .232.544a.51.51 0 0 0 .596-.06c.009-.008 1.013-.863 4.657-.863c3.59 0 4.617.83 4.656.863a.5.5 0 0 0 .829-.484");
}

.j_ykwbb4m {
  cx: 24.5px;
  cy: 16.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.vrd83_b4t {
  cx: 11.5px;
  cy: 16.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

</style>
