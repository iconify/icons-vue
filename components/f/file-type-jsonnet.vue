<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qjxjrgc7m"/><path class="fex23nbsh"/><path class="dkmcoccch"/><path class="imu4ilmtt"/><path class="uma0t627b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-jsonnet" /></template>
<style>
.dkmcoccch {
  fill: var(--svg-color--bfbfbf, #bfbfbf);
  fill-rule: evenodd;
  d: path("M7.012 12.732L10.28 11.1l3.269 1.635l-3.269 1.631ZM10.28 11.1l3.269-1.634l3.268 1.634l-3.268 1.635Zm3.269 4.9l3.268-1.634L20.086 16l-3.269 1.634Zm3.268-4.9l3.269-1.634l3.268 1.634l-3.268 1.635Zm0 6.537L20.086 16l3.268 1.634l-3.268 1.634Z");
}

.fex23nbsh {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20.086 22.537L16.817 20.9v-3.266l3.269 1.634Z");
}

.imu4ilmtt {
  fill: var(--svg-color--gray, gray);
  fill-rule: evenodd;
  d: path("M13.549 22.537v-3.269l3.268-1.634V20.9ZM20.086 16v-3.268l3.268-1.632v3.269Zm0 6.537v-3.269l3.268-1.634V20.9ZM16.817 20.9v-3.266L20.086 16v3.268ZM13.549 16v-3.268l3.268-1.632v3.269Z");
}

.qjxjrgc7m {
  fill: var(--svg-color--0064bd, #0064bd);
  d: path("M30 16A14 14 0 1 1 16 2a14 14 0 0 1 14 14");
}

.uma0t627b {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m7.012 16l3.268 1.634V20.9l3.269 1.634v-3.266l3.268 1.632v-3.266L13.549 16v-3.268L10.28 11.1v3.269l-3.268-1.637Zm13.074 0l-3.269-1.634V11.1l3.269 1.635Z");
}

</style>
