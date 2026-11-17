<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkd3fac_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-pause-quarter-fill-round" /></template>
<style>
.jkd3fac_g {
  fill: currentColor;
  d: path("M10.436 2.123a10 10 0 0 1 11.441 11.441a1 1 0 0 1-1.51.697a1 1 0 0 1-.465-1.01Q20 12.63 20 12a7.9 7.9 0 0 0-.609-3.061a7.9 7.9 0 0 0-1.734-2.596a7.98 7.98 0 0 0-6.908-2.245a1 1 0 1 1-.313-1.975M3.91 6.122A10 10 0 0 1 6.122 3.91a1 1 0 1 1 1.176 1.618a8 8 0 0 0-1.77 1.77A1 1 0 1 1 3.91 6.122M11 9v6a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0m4 0v6a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0M2.123 13.564a10 10 0 0 1 0-3.128a1 1 0 0 1 1.975.313a8 8 0 0 0 0 2.502a1 1 0 1 1-1.975.313m3.999 6.526a10 10 0 0 1-2.212-2.212a1 1 0 1 1 1.618-1.176a8 8 0 0 0 1.77 1.77a1.002 1.002 0 0 1-1.176 1.618m13.968-2.212a10 10 0 0 1-2.212 2.212a1 1 0 1 1-1.176-1.618a8 8 0 0 0 1.77-1.77a1.002 1.002 0 0 1 1.618 1.176m-9.654 3.999a1 1 0 0 1 .313-1.975a8 8 0 0 0 2.502 0a1 1 0 1 1 .313 1.975a10 10 0 0 1-3.128 0");
}

</style>
