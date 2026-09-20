<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cffe1qtso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-starburst-16-filled" /></template>
<style>
.cffe1qtso {
  fill: currentColor;
  d: path("M4.102 2.25a2 2 0 0 1 2.645-1.083l.887.385a1 1 0 0 0 .786.003l.89-.377a2 2 0 0 1 2.636 1.105l.356.899a1 1 0 0 0 .553.558l.896.363a2 2 0 0 1 1.082 2.646l-.384.887a1 1 0 0 0-.003.786l.376.89a2 2 0 0 1-1.105 2.636l-.899.356a1 1 0 0 0-.558.553l-.362.896a2 2 0 0 1-2.646 1.082l-.887-.384a1 1 0 0 0-.787-.004l-.89.377a1.997 1.997 0 0 1-2.635-1.105l-.356-.899a1 1 0 0 0-.553-.558l-.896-.363a2 2 0 0 1-1.083-2.646l.385-.886a1 1 0 0 0 .003-.787l-.377-.89A2 2 0 0 1 2.28 4.055l.899-.356a1 1 0 0 0 .558-.554zm6.752 3.896a.5.5 0 0 0-.707 0L7.25 9.043L5.854 7.646a.5.5 0 0 0-.708.708l1.75 1.75a.5.5 0 0 0 .708 0l3.25-3.25a.5.5 0 0 0 0-.708");
}

</style>
