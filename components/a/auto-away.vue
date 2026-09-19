<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ns1rcpslj"/><path class="imhd_ncgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:auto-away" /></template>
<style>
.imhd_ncgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.09 27.266l-3.149-9.865l-3.269 9.865m1.089-3.329h4.238m9.67-3.221l-2.058 6.535l-1.937-6.535l-2.059 6.535l-1.937-6.535m19.35 6.553l-2.543-6.535m4.843 0L35.3 29.612c-.242.617-.726.987-1.332.987h-.363m-2.497-5.809c0 1.356-1.09 2.466-2.422 2.466s-2.421-1.11-2.421-2.466v-1.603c0-1.357 1.09-2.467 2.421-2.467s2.422 1.11 2.422 2.466m.968 4.07c-.484 0-.968-.493-.968-.987V20.72M33.85 42.5l8.65-8.317");
}

.ns1rcpslj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h24.35v-8.317h8.65V9.5a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
  opacity: var(--svg-opacity--0-995, 0.995);
}

</style>
