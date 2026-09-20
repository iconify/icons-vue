<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":286};
const content = `<defs><linearGradient id="SVGbO4fAb2v" x1="77.041%" x2="22.841%" y1="13.184%" y2="87.539%"><stop offset="0%" class="wdkw33b7c"/><stop offset="100%" class="ksvh7y_-l"/></linearGradient></defs><path fill="url(#SVGbO4fAb2v)" class="mkaenvpqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:dockbit" /></template>
<style>
.ksvh7y_-l {
  stop-color: var(--svg-color--3f37ae, #3f37ae);
}

.mkaenvpqi {
  d: path("M240.481 60.13L143.525 4.16a31.05 31.05 0 0 0-31.046 0L15.523 60.13A31.06 31.06 0 0 0 0 87.018v111.955c0 11.09 5.92 21.338 15.523 26.883l96.956 55.984a31.05 31.05 0 0 0 31.046 0l96.956-55.984A31.04 31.04 0 0 0 256 198.973V87.018a31.06 31.06 0 0 0-15.519-26.888m-9.315 135.918a9.32 9.32 0 0 1-4.658 8.07l-22.684 13.098a9.32 9.32 0 0 1-9.315 0l-22.688-13.098a9.32 9.32 0 0 1-4.654-8.07v-26.196c0-3.329 1.775-6.4 4.654-8.066l22.688-13.098a9.32 9.32 0 0 1 9.315 0l22.684 13.098a9.31 9.31 0 0 1 4.658 8.066z");
}

.wdkw33b7c {
  stop-color: var(--svg-color--7236dc, #7236dc);
}

</style>
