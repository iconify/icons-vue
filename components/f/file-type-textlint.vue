<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(2.02 2.02)scale(.87375)"><path class="oy_mq4bne"/><linearGradient id="SVGtvmt2dZP" x1="24.81" x2="24.81" y1="24.81" y2="11.11" gradientUnits="userSpaceOnUse"><stop offset="0" class="e825e26io"/><stop offset="1" class="vcr8t9iqi"/></linearGradient><path fill="url(#SVGtvmt2dZP)" class="zmg5-f_0m"/><linearGradient id="SVG0SZzFcGN" x1="7.19" x2="7.19" y1="7.19" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset="0" class="tdx55c_vw"/><stop offset="1" class="opud24xap"/></linearGradient><path fill="url(#SVG0SZzFcGN)" class="l64nckb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-textlint" /></template>
<style>
.e825e26io {
  stop-color: var(--svg-color--f28b95, #f28b95);
}

.l64nckb5l {
  d: path("M7.2 7.2h17.6v3.91h-6.82v13.7h-3.96v-13.7H7.2Z");
}

.opud24xap {
  stop-color: var(--svg-color--3c84b0, #3c84b0);
}

.oy_mq4bne {
  fill: var(--svg-color--f4f4f4, #f4f4f4);
  d: path("M16 32a16 16 0 1 0 0-32a16 16 0 0 0 0 32");
}

.tdx55c_vw {
  stop-color: var(--svg-color--28ebf8, #28ebf8);
}

.vcr8t9iqi {
  stop-color: var(--svg-color--f34c6f, #f34c6f);
}

.zmg5-f_0m {
  d: path("M11.11 11.11H7.2v13.7h17.62v-3.92H11.1Z");
}

</style>
