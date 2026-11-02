<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pd583sppo"/><path class="pbtlsebpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-sun-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pbtlsebpl {
  d: path("M11 3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0ZM4.929 6.343a.999.999 0 1 1 1.414-1.414l1.414 1.414a1 1 0 0 1-1.412 1.416l-.001-.001l-.001-.001Zm12.728-1.414a1 1 0 0 1 1.414 1.414l-1.414 1.414a1 1 0 0 1-1.416-1.412l.002-.002Zm-2.843 7.54a1 1 0 0 1-.844-.817a2 2 0 0 0-.336-.806a1.995 1.995 0 0 0-2.35-.713a1 1 0 0 1-1.292-1.292l.001-.001a1 1 0 0 1 .575-.575a4.002 4.002 0 0 1 5.372 3.04a1 1 0 0 1-1.124 1.164ZM19 11h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2");
}

.pd583sppo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.667 22a3.668 3.668 0 0 1-.7-7.267a4.7 4.7 0 0 1 1.913-2.071a4.84 4.84 0 0 1 3.102-.568c2.138.322 3.657 1.935 3.959 4.057A3 3 0 0 1 13 22Z");
}

</style>
