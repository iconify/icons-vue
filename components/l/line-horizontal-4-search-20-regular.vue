<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g2rz7ibpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-search-20-regular" /></template>
<style>
.g2rz7ibpw {
  fill: currentColor;
  d: path("M12.5 10a4.48 4.48 0 0 0 2.809-.984l3.837 3.838a.5.5 0 0 0 .708-.708L16.016 8.31A4.5 4.5 0 1 0 12.5 10m0-8a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7m.02 9h3.359l1 1H2.5a.5.5 0 0 1 0-1zM2.5 3h5.1a5.5 5.5 0 0 0-.393 1H2.5a.5.5 0 0 1 0-1m5.1 5a5.5 5.5 0 0 1-.393-1H2.5a.5.5 0 0 0 0 1zM2 15.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5");
}

</style>
