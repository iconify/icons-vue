<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n86lsgb8q"/><path class="jinnscgfe"/><path class="bzxf38oep"/><path class="uxwixwbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-jupyter" /></template>
<style>
.bzxf38oep {
  fill: var(--svg-color--9e9e9e, #9e9e9e);
  d: path("M10.2 27.739a2.109 2.109 0 1 1-.2-.8a2.1 2.1 0 0 1 .2.8");
}

.jinnscgfe {
  fill: var(--svg-color--f37726, #f37726);
  d: path("M16.375 23.111c-4.487 0-8.43-1.61-10.469-3.988a11.162 11.162 0 0 0 20.938 0c-2.034 2.377-5.962 3.988-10.469 3.988m0-15.463c4.487 0 8.43 1.61 10.469 3.988a11.162 11.162 0 0 0-20.938 0c2.039-2.383 5.963-3.988 10.469-3.988");
}

.n86lsgb8q {
  fill: var(--svg-color--767677, #767677);
  d: path("M26.233 3.588A1.69 1.69 0 1 1 24.473 2a1.67 1.67 0 0 1 1.76 1.585Z");
}

.uxwixwbis {
  fill: var(--svg-color--616262, #616262);
  d: path("M6.416 7.106A1.226 1.226 0 1 1 7.608 5.83a1.24 1.24 0 0 1-1.192 1.276");
}

</style>
