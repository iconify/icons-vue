<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x_itklb5u"/><path class="e2xhjzbpf"/><g class="ihe_ixbsy"><path class="pl_ghacti"/><path class="wqte9tb7a"/></g><g class="i5t9fab6a"><path class="qg4gp2_jy"/><path class="qoyo93bhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-postgres" /></template>
<style>
.e2xhjzbpf {
  fill: var(--svg-color--336791, #336791);
  d: path("M26.3 19.861c-2.8.583-3-.4-3-.4c3-4.4 4.2-10.1 3.1-11.4c-2.9-3.8-8-2-8.1-1.9l-.03.005a10 10 0 0 0-1.9-.196c-1.3-.02-2.2.335-3 .893c0 0-9.1-3.7-8.7 4.7c.1 1.8 2.6 13.6 5.5 10.018a55 55 0 0 1 2.1-2.402c.5.3 1.1.5 1.8.458l.1-.043c-.02.162-.01.3.2.5c-.8.852-.5 1-2.1 1.3c-1.5.318-.6.884-.04 1c.717.2 2.4.433 3.5-1.1l-.04.179c.299.2.5 1.6.473 2.8c-.04 1.2-.1 2 .177 2.6c.236.6.5 2.1 2.5 1.6c1.7-.4 2.5-1.3 2.7-2.8c.1-1.1.3-.9.3-1.9l.2-.467c.2-1.5.028-2 1.1-1.8l.2.022c.8.03 1.8-.1 2.3-.4c1.3-.6 2-1.6.762-1.3Z");
}

.i5t9fab6a {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--fff, #fff);
}

.ihe_ixbsy {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-7px, 0.7px);
}

.pl_ghacti {
  stroke-linejoin: bevel;
  d: path("M23.3 19.5s.2 1 3 .3c1.2-.2.5.7-.8 1.3c-1 .5-3.3.6-3.3 0c-.1-1.7 1.2-1.2 1-1.6c0-.4-.6-.8-1-1.8c-.3-.8-4.6-7 1.2-6.1c.2 0-1.5-5.6-7-5.7c-5.4 0-5.3 6.7-5.3 6.7");
}

.qg4gp2_jy {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.4 12.6q0 .3.5.4q.7 0 .6-.3q0-.1-.5-.2z");
}

.qoyo93bhe {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.4 12.4s-.2.4-.5.4q-.5 0-.6-.3l.5-.3q.5 0 .6.2Z");
}

.wqte9tb7a {
  stroke-linejoin: round;
  d: path("M15.9 20.7c-.1 2.8 0 5.6.2 6.3s.9 2 2.9 1.6q2.4-.5 2.6-2.6l.6-5M13.5 6.9S4.4 3 4.8 11.5c0 1.8 2.6 13.6 5.5 10l2-2.3m6-13.1c-.3 0 5.1-2 8.1 2c1.1 1.3-.1 7-3.1 11.4m-9 .5c-.7.9-.5 1-2 1.4c-1.6.3-.7.8 0 1s2.3.4 3.4-1.2c.4-.4 0-1.2-.5-1.4q-.3-.2-.9.2m0 0q-.1-.7.4-1.8c.4-1 1.3-2 .6-5.4c-.6-2.5-4.2-.5-4.2-.2q.2.8 0 3.3c-.3 2.1 1.3 3.9 3.1 3.7m9.2-8l-.2 2.4c0 1.4.7 3-.4 4.6");
}

.x_itklb5u {
  fill: none;
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--2-1px, 2.1px);
  d: path("M21.9 22.8c.2-1.3.112-1.5 1.1-1.3l.2.02c.8.03 1.8-.1 2.3-.4c1.3-.6 2-1.6.763-1.3c-2.8.582-3-.4-3-.4c3-4.4 4.2-10.1 3.1-11.4c-2.9-3.8-8-2-8.1-1.9l-.03.005a10 10 0 0 0-1.9-.196c-1.3-.02-2.2.3-3 .893c0 0-9.1-3.7-8.7 4.7c.1 1.8 2.6 13.6 5.5 10c1.1-1.3 2.1-2.4 2.1-2.4c.5.3 1.1.521 1.8.458l.1-.043c-.01.162-.01.3.2.5c-.8.852-.5 1-2.1 1.3c-1.5.318-.6.884-.04 1c.717.2 2.4.433 3.5-1.1l-.04.179c.3.2.3 1.7.3 2.8s.1 2 .329 2.628c.215.6.5 2.1 2.5 1.6c1.7-.4 3-.9 3.1-5.7");
}

</style>
