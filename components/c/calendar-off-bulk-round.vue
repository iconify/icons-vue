<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m5qf0kbcw"/><path class="o6sgqymxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m5qf0kbcw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.243 4H16c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 9a1 1 0 0 1-1 1h-5.757Zm-3.244.999L10 10H4a1 1 0 0 1-1-1a5 5 0 0 1 .393-1.947c.346-.813.9-1.522 1.606-2.054");
}

.o6sgqymxx {
  d: path("M21.293 22.707L19.086 20.5c-.822.898-1.841 1.5-3.086 1.5H8a5 5 0 0 1-1.94-.39l-.007-.003A4.995 4.995 0 0 1 3 17V9c0-1.254.604-2.266 1.5-3.086L1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414M11 4h4V3a1 1 0 0 1 2 0v1.099A5.01 5.01 0 0 1 21 9v5a1 1 0 0 1-2 0V9a3 3 0 0 0-3-3h-5a1 1 0 0 1 0-2M5 9v8a3.004 3.004 0 0 0 3 3h8c.689 0 1.229-.417 1.67-.916L5.916 7.33C5.422 7.767 5 8.308 5 9");
}

</style>
