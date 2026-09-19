<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="zpmtr0f-y"><path class="zwt7u4bfw"/><path class="b1amytbfx"/></g><path class="dc-u7hbpc"/><path class="ztbslnd5j"/><g transform="translate(2)"><circle class="y5go7pbqp"/><path class="ljnld79od"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:left-pointing-magnifying-glass" /></template>
<style>
.b1amytbfx {
  d: path("M45.603 21.691c0 11.989-9.718 21.691-21.693 21.691c-11.977 0-21.693-9.702-21.693-21.691S11.933 0 23.91 0c11.975 0 21.693 9.702 21.693 21.691");
}

.dc-u7hbpc {
  fill: var(--svg-color--30434a, #30434a);
  d: path("M43.4 21.691c0 10.766-8.731 19.485-19.489 19.485S4.424 32.457 4.424 21.691c0-10.77 8.728-19.485 19.487-19.485S43.4 10.921 43.4 21.691");
}

.ljnld79od {
  fill: var(--svg-color--27a8e0, #27a8e0);
  d: path("M13.557 8.956a15.18 15.18 0 0 0-6.852 12.702c0 8.396 6.807 15.205 15.205 15.205c.148 0 .297-.02.445-.024C7.44 29.446 11.124 14.095 13.557 8.956");
}

.y5go7pbqp {
  cx: 21.91px;
  cy: 21.691px;
  r: 15.205px;
  fill: var(--svg-color--57c6e9, #57c6e9);
}

.zpmtr0f-y {
  fill: var(--svg-color--243438, #243438);
}

.ztbslnd5j {
  fill: var(--svg-color--1e75bb, #1e75bb);
  d: path("M41.26 21.691c0 9.583-7.769 17.344-17.347 17.344c-9.574 0-17.345-7.762-17.345-17.344c0-9.585 7.771-17.345 17.345-17.345c9.578 0 17.347 7.76 17.347 17.345");
}

.zwt7u4bfw {
  d: path("M44.52 63.35c-1.553.746-3.034.886-3.312.308l-15.962-33.08c-.277-.576.753-1.652 2.308-2.403c1.551-.747 3.039-.888 3.314-.308l15.96 33.08c.276.575-.758 1.656-2.308 2.406");
}

</style>
