<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cdq-oac6h"/><path class="za_waibcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lark" /></template>
<style>
.cdq-oac6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.12 28.112c3.334-2.18 6.279-4.534 9.221-7.697c3.538-3.802 10.864-3.89 14.159-1.688c-3.386 3.143-2.997 7.08-7.319 11.119C29.47 36.118 11.164 24.712 4.5 17.303v17.043c4.117 4.107 11.46 6.126 18.383 4.537c5.687-1.306 12.034-5.238 15.618-11.771");
}

.za_waibcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.785 17.818c-.914-3.107-2.318-6.53-5.163-9.243H10.324c6.318 4.154 11.51 10.398 14.352 16.127");
}

</style>
