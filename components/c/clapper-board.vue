<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w1377fvbc"/><path class="m5nofgb_x"/><path class="ftvbzyu2k"/><path class="a153jxbsu"/><path class="gb5h4dlxg"/><path class="n3lpuhhjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:clapper-board" /></template>
<style>
.a153jxbsu {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M1.845 15h4l-4 7zm11 0l-4 7h7l4-7zm14 0l-4 7h7l4-7z");
}

.ftvbzyu2k {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M1.845 15h34v7h-34z");
}

.gb5h4dlxg {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M.155 8.207L33.148 0l1.69 6.792L1.845 15z");
}

.m5nofgb_x {
  fill: var(--svg-color--3f7123, #3f7123);
  d: path("M1.845 15h34v6h-34z");
}

.n3lpuhhjf {
  fill: var(--svg-color--292f33, #292f33);
  d: path("m.155 8.207l5.572 5.827L1.845 15zm19.158 2.448l-5.572-5.828l-6.793 1.69l5.572 5.828zm13.586-3.38l-5.572-5.828l-6.793 1.69l5.572 5.827z");
}

.w1377fvbc {
  fill: var(--svg-color--3f7123, #3f7123);
  d: path("M35.845 32c0 2.2-1.8 4-4 4h-26c-2.2 0-4-1.8-4-4V19c0-2.2 1.8-4 4-4h26c2.2 0 4 1.8 4 4z");
}

</style>
