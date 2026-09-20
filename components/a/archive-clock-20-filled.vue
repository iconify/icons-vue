<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="d2zdb4bdt"/><path class="syj3y85gj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-clock-20-filled" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d2zdb4bdt {
  d: path("M19 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M14.5 12a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H16a.5.5 0 0 0 0-1h-1v-1.5a.5.5 0 0 0-.5-.5");
}

.syj3y85gj {
  d: path("M17 9.6c-.75-.383-1.6-.6-2.5-.6c-1.177 0-2.266.37-3.16 1H8.5a.5.5 0 0 0 0 1h1.758A5.48 5.48 0 0 0 9 14.5c0 .9.218 1.75.602 2.5H6a3 3 0 0 1-3-3V8h14zM16.75 3c.69 0 1.25.56 1.25 1.25v1.5C18 6.44 17.44 7 16.75 7H3.25C2.56 7 2 6.44 2 5.75v-1.5C2 3.56 2.56 3 3.25 3z");
}

</style>
