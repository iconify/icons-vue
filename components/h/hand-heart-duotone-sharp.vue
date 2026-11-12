<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t2wwfbc_q"/><path class="ildf9hb3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-heart-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ildf9hb3v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 16l3-3c.6-.6 1.2-1 2-1h3a2 2 0 1 1 0 4h-2m4-2l3-3a2.121 2.121 0 1 1 3 3l-5 5c-.64.64-1.36 1-2 1H8m-5-5l6 6m3-17c-2-2-5 0-3 2l3 3l3-3c2-2-1-4-3-2");
}

.t2wwfbc_q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 2.725c1.071-.675 2.476-.776 3.555-.057c.3.197.555.456.748.76c.204.319.324.685.351 1.063c.06.854-.358 1.627-.947 2.216l-3 3a1 1 0 0 1-1.414 0l-3-3c-.589-.589-1.007-1.362-.947-2.216c.027-.378.147-.744.351-1.063c.193-.304.448-.563.748-.76c1.079-.719 2.484-.618 3.555.057");
}

</style>
