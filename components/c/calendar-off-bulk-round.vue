<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iww_o9t9p"/><path class="juwqdkbks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iww_o9t9p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.291 5.705A1 1 0 0 1 11 4h5c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 9a1 1 0 0 1-1 1h-5.414Zm-5.292-.706L10 10H4a1 1 0 0 1-1-1a5 5 0 0 1 .393-1.947c.346-.813.9-1.522 1.606-2.054");
}

.juwqdkbks {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-1.969-1.969A5.02 5.02 0 0 1 16 22H8a5 5 0 0 1-5-5V9c0-1.222.451-2.409 1.262-3.324L1.293 2.707a.999.999 0 1 1 1.414-1.414M15 3a1 1 0 0 1 2 0v1.099A5.01 5.01 0 0 1 21 9v5a1 1 0 0 1-2 0V9a3 3 0 0 0-3-3h-5a1 1 0 0 1 0-2h4ZM5 9v8a3 3 0 0 0 3 3h8c.694 0 1.369-.241 1.905-.681L5.681 7.095A3 3 0 0 0 5 9");
}

</style>
