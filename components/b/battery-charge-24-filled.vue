<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs3gi9brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-charge-24-filled" /></template>
<style>
.rs3gi9brh {
  fill: currentColor;
  d: path("M7.64 7.116v.001A1.3 1.3 0 0 0 8.8 9.004H10V11.6c0 1.474 1.983 1.945 2.648.632l2.71-5.344l.07-.163c.086-.244.09-.494.035-.726H17a3 3 0 0 1 3 3v1h1.001a.996.996 0 0 1 1 1v2a1 1 0 0 1-1 1H20v1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h3.206zm3.602-4.893c.19-.376.757-.24.757.18V6H14.2a.3.3 0 0 1 .268.437l-2.71 5.344c-.19.376-.757.24-.757-.18V8.004H8.8a.3.3 0 0 1-.268-.436z");
}

</style>
