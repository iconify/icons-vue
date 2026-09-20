<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w6po8kbfw"/><path class="w4_63ubgd"/><path class="sr1zv8bky"/><path class="yv8_ayy1s"/><path class="k7dhs0c1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-view-opened" /></template>
<style>
.k7dhs0c1h {
  fill: var(--svg-color--fff, #fff);
  d: path("m20.99 24.011l-6-3.607v-1.307l6-3.608v2.023l-3.828 2.238l3.828 2.239zm1.5-.002v-2.021l3.855-2.238l-3.855-2.237v-2.022l6 3.591v1.336z");
}

.sr1zv8bky {
  fill: var(--svg-color--e44f26, #e44f26);
  d: path("M14.167 28.901L12.482 10h18.516l-1.687 18.898L21.729 31z");
}

.w4_63ubgd {
  fill: var(--svg-color--db917b, #db917b);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.w6po8kbfw {
  fill: var(--svg-color--db917b, #db917b);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.yv8_ayy1s {
  fill: var(--svg-color--f1662a, #f1662a);
  d: path("m21.74 29.393l6.127-1.699l1.442-16.149H21.74z");
}

</style>
