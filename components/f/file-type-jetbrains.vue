<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><defs><linearGradient id="SVGEDDnMbnv" x1=".85" x2="62.62" y1="62.72" y2="1.81" gradientUnits="userSpaceOnUse"><stop offset="0" class="ec6hdqb4b"/><stop offset=".43" class="cm-b0x9yw"/><stop offset=".99" class="fxr1xyban"/></linearGradient></defs><path fill="url(#SVGEDDnMbnv)" transform="translate(2 2)scale(.4375)" class="imyc9yulz"/><path class="t63aesbfh"/><path class="mjo7-bcbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-jetbrains" /></template>
<style>
.cm-b0x9yw {
  stop-color: var(--svg-color--ff021d, #ff021d);
}

.ec6hdqb4b {
  stop-color: var(--svg-color--ff9419, #ff9419);
}

.ft5dv1b6b {
  fill: none;
}

.fxr1xyban {
  stop-color: var(--svg-color--e600ff, #e600ff);
}

.imyc9yulz {
  d: path("M20.34 3.66L3.66 20.34A12.5 12.5 0 0 0 0 29.18V59c0 2.76 2.24 5 5 5h29.82c3.32 0 6.49-1.32 8.84-3.66l16.68-16.68c2.34-2.34 3.66-5.52 3.66-8.84V5c0-2.76-2.24-5-5-5H29.18c-3.32 0-6.49 1.32-8.84 3.66");
}

.mjo7-bcbu {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.125 22.563H7.688v1.75h7.437z");
}

.t63aesbfh {
  fill: var(--svg-color--000, #000);
  d: path("M23 9H5.5v17.5H23z");
}

</style>
