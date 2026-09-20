<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx835xyiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-24-regular" /></template>
<style>
.lx835xyiq {
  fill: currentColor;
  d: path("M18.01 12.194a.713.713 0 0 1 .98 0c.652.651 1.907 1.686 3.45 1.899c.307.042.56.285.56.589v2.838c0 3.816-3.58 5.2-4.353 5.456a.46.46 0 0 1-.293 0C17.578 22.72 14 21.336 14 17.52v-2.838c0-.304.253-.547.56-.59c1.543-.212 2.798-1.247 3.45-1.898M12 1a5 5 0 0 1 5 5v2.01a3.25 3.25 0 0 1 3 3.24v.526a8 8 0 0 1-.31-.289A1.7 1.7 0 0 0 18.48 11a1.75 1.75 0 0 0-1.73-1.5h-9.5a1.75 1.75 0 0 0-1.75 1.75v7.5c0 .966.784 1.75 1.75 1.75h6.483q.438.812 1.124 1.5H7.25A3.25 3.25 0 0 1 4 18.75v-7.5a3.25 3.25 0 0 1 3-3.24V6a5 5 0 0 1 5-5m0 12.75c.437 0 .822.225 1.045.565q-.043.174-.045.37v1.062a1.25 1.25 0 1 1-1-1.997M12 2.5A3.5 3.5 0 0 0 8.5 6v2h7V6A3.5 3.5 0 0 0 12 2.5");
}

</style>
