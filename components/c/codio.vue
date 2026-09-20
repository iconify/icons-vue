<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":296};
const content = `<path class="a9pxamv5n"/><path class="y5l5hpa0t"/><path class="pvqv_4bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:codio" /></template>
<style>
.a9pxamv5n {
  fill: var(--svg-color--a3baf0, #a3baf0);
  d: path("m125.306 214.373l.934 77.731l1.68 3.46l127.679-73.75l-72.306-41.811l-55.373 31.94z");
}

.pvqv_4bnf {
  fill: var(--svg-color--c7d6f7, #c7d6f7);
  d: path("m2.966 75.967l67.378 38.918l2.283 1.318l55.293-31.94l55.373 31.94l72.306-41.81L127.919.641L.242 74.392z");
}

.y5l5hpa0t {
  fill: var(--svg-color--4474e1, #4474e1);
  d: path("m.24 221.813l127.68 73.75v-83.54l-55.293-31.94v-67L4.955 74.393H.24z");
}

</style>
