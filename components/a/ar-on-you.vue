<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayu8z9b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ar-on-you" /></template>
<style>
.ayu8z9b8f {
  fill: currentColor;
  d: path("M17.675 6.325Q20 8.65 20 12t-2.325 5.675T12 20t-5.675-2.325T4 12t2.325-5.675T12 4t5.675 2.325m-3.525 8.488q.95-.688 1.35-1.813h-7q.4 1.125 1.35 1.813T12 15.5t2.15-.687m-5.363-4.1Q9.076 11 9.5 11t.713-.288T10.5 10t-.288-.712T9.5 9t-.712.288T8.5 10t.288.713m5 0q.287.287.712.287t.713-.288T15.5 10t-.288-.712T14.5 9t-.712.288T13.5 10t.288.713M1 6V3q0-.825.588-1.412T3 1h3v2H3v3zm5 17H3q-.825 0-1.412-.587T1 21v-3h2v3h3zm12 0v-2h3v-3h2v3q0 .825-.587 1.413T21 23zm3-17V3h-3V1h3q.825 0 1.413.588T23 3v3z");
}

</style>
