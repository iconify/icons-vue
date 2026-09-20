<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow29fs6la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ar-on-you-sharp" /></template>
<style>
.ow29fs6la {
  fill: currentColor;
  d: path("M17.675 6.325Q20 8.65 20 12t-2.325 5.675T12 20t-5.675-2.325T4 12t2.325-5.675T12 4t5.675 2.325m-3.525 8.488q.95-.688 1.35-1.813h-7q.4 1.125 1.35 1.813T12 15.5t2.15-.687m-5.363-4.1Q9.076 11 9.5 11t.713-.288T10.5 10t-.288-.712T9.5 9t-.712.288T8.5 10t.288.713m5 0q.287.287.712.287t.713-.288T15.5 10t-.288-.712T14.5 9t-.712.288T13.5 10t.288.713M1 6V1h5v2H3v3zm0 17v-5h2v3h3v2zm17 0v-2h3v-3h2v5zm3-17V3h-3V1h5v5z");
}

</style>
