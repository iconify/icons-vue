<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vutngg5hp"/><path class="fbbq9ja8n"/><path class="v6imahbda"/><path class="zufwpd78h"/><path class="tkejy28py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-aspx" /></template>
<style>
.fbbq9ja8n {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M27.43 26.8H9.49V4.24h11.28v6.75h6.75v15.8z");
}

.tkejy28py {
  fill: var(--svg-color--33a9dc, #33a9dc);
  stroke: var(--svg-color--33a9dc, #33a9dc);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-96px, 0.96px);
  d: path("M9.29 28.1a24.5 24.5 0 0 1-.52-17.78l.75.32a23.7 23.7 0 0 0 .51 17.14Zm6.8 0l-.74-.32a23.7 23.7 0 0 0 .51-17.14l.75-.32a24.5 24.5 0 0 1-.51 17.79ZM12.3 9.65h.86v19.64h-.86z");
}

.v6imahbda {
  fill: var(--svg-color--33a9dc, #33a9dc);
  d: path("M12.72 29.97a10.7 10.7 0 1 1 10.7-10.7a10.7 10.7 0 0 1-10.7 10.7m0-19.57a8.87 8.87 0 1 0 8.87 8.88a8.9 8.9 0 0 0-8.87-8.87Z");
}

.vutngg5hp {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M22.99 2.02H7.18v27h22.46V8.77z");
}

.zufwpd78h {
  fill: var(--svg-color--33a9dc, #33a9dc);
  stroke: var(--svg-color--33a9dc, #33a9dc);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-96px, 0.96px);
  d: path("M3.08 18.85h19.29v.86H3.08zm9.86-3.56a31 31 0 0 1-8.18-1.07l.23-.78a30.3 30.3 0 0 0 15.42 0l.23.78a27 27 0 0 1-7.7 1.07ZM5 24.89l-.23-.77a30.5 30.5 0 0 1 15.88 0l-.23.77A30.3 30.3 0 0 0 5 24.9Z");
}

</style>
