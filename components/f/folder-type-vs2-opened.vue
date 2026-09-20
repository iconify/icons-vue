<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o4k-o_zcb"/><path class="lo9io1bdl"/><path class="plyrzpe-j"/><path class="p0vi4l8dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-vs2-opened" /></template>
<style>
.lo9io1bdl {
  fill: var(--svg-color--c67bdb, #c67bdb);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.o4k-o_zcb {
  fill: var(--svg-color--c67bdb, #c67bdb);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.p0vi4l8dh {
  fill: var(--svg-color--fff, #fff);
  d: path("m20.596 20.489l5.312-3.975v7.979l-5.319-4.004zm-8.509 2.405v-4.781l2.66 2.376z");
}

.plyrzpe-j {
  fill: var(--svg-color--68217a, #68217a);
  d: path("M30.966 11.741L26.618 10l-9.4 9.159l-5.745-4.37l-1.24.628V25.6l1.233.62l5.737-4.37L26.618 31l4.348-1.741zM12.087 22.894v-4.781l2.66 2.376Zm8.513-2.405l5.312-3.974v7.979l-5.319-4Z");
}

</style>
