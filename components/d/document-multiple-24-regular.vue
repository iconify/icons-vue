<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i8ft8gbsh"/><path class="bj39x4bwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-multiple-24-regular" /></template>
<style>
.bj39x4bwr {
  d: path("M6.629 20.5A2.25 2.25 0 0 0 8.75 22h6.5A4.75 4.75 0 0 0 20 17.25v-5.881a2.25 2.25 0 0 0-.66-1.591l-.84-.841v8.313a3.25 3.25 0 0 1-3.25 3.25z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.i8ft8gbsh {
  d: path("M4 4.25A2.25 2.25 0 0 1 6.25 2h4.381a2.25 2.25 0 0 1 1.591.659l4.619 4.619c.422.422.659.994.659 1.59v8.382a2.25 2.25 0 0 1-2.25 2.25h-9A2.25 2.25 0 0 1 4 17.25zm2.25-.75a.75.75 0 0 0-.75.75v13c0 .414.336.75.75.75h9a.75.75 0 0 0 .75-.75V8.998h-3.246a2.25 2.25 0 0 1-2.25-2.25V3.5zm5.754 1.062v2.186c0 .414.336.75.75.75h2.185z");
}

</style>
