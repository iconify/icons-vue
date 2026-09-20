<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j2j59qyry"/><path class="byjd56bst"/><path class="gb_nz3b9b"/><path class="rms2wz4zz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dsla" /></template>
<style>
.byjd56bst {
  fill: var(--svg-color--f69d88, #f69d88);
  d: path("M13.13 3.613h-2.252a7.254 7.254 0 0 0-7.26 7.264v2.253a7.25 7.25 0 0 0 7.255 7.254h2.253a7.25 7.25 0 0 0 7.254-7.254v-2.253a7.25 7.25 0 0 0-7.254-7.254z");
}

.ft5dv1b6b {
  fill: none;
}

.gb_nz3b9b {
  fill: var(--svg-color--2196f3, #2196f3);
  d: path("M12.005 20.218a8.217 8.217 0 1 0 0-16.434a8.217 8.217 0 0 0 0 16.434");
}

.j2j59qyry {
  fill: var(--svg-color--ffe1a5, #ffe1a5);
  d: path("m4.84 6.979l-.774 1.324A7.955 7.955 0 0 0 6.979 19.17l1.324.764a7.955 7.955 0 0 0 10.867-2.913l.764-1.324A7.95 7.95 0 0 0 17.022 4.83l-1.325-.764A7.954 7.954 0 0 0 4.83 6.979z");
}

.rms2wz4zz {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("m15.478 6.047l-2.53 4.326l2.486 1.499l-6.902 6.083l2.5-4.351l-2.5-1.454z");
}

</style>
