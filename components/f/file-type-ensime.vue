<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="loz8bnb3r"/><path class="vr5nfdb9r"/><path class="djd3i-btr"/><path class="v2sue1boh"/><path class="uhf7d_bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ensime" /></template>
<style>
.djd3i-btr {
  fill: var(--svg-color--f1626b, #f1626b);
  d: path("M15.975 14.772L3.695 8.411v6.361l12.281 6.411l12.281-6.411V8.411Z");
}

.loz8bnb3r {
  fill: none;
  d: path("m22.116 11.554l-6.14 3.218l-6.14-3.218l6.14-3.168Z");
}

.uhf7d_bsl {
  fill: var(--svg-color--f1626b, #f1626b);
  d: path("m3.695 17.228l12.281 6.361V30L3.695 23.589Z");
}

.v2sue1boh {
  fill: var(--svg-color--ef4551, #ef4551);
  d: path("M22.116 20.421L9.811 26.782L16 30l12.305-6.386Z");
}

.vr5nfdb9r {
  fill: var(--svg-color--232f3f, #232f3f);
  d: path("m15.975 2l12.281 6.361v6.411L15.975 8.361l-12.28 6.411V8.361L9.86 5.168z");
}

</style>
