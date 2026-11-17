<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fkp926bqa"/><path class="od35trtci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:iron-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fkp926bqa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 16a3 3 0 0 1-3 3H4a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l5-5C9.008 10.578 9.961 10 11 10h10a1 1 0 0 1 1 1Z");
}

.od35trtci {
  d: path("M19 7h-2a.997.997 0 0 0-1 1v3a1 1 0 0 1-2 0V7.999c0-.796.317-1.56.881-2.122A3 3 0 0 1 17 5h2a3.004 3.004 0 0 1 3 3v3a1 1 0 0 1-2 0V7.999A1 1 0 0 0 19 7");
}

</style>
