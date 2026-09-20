<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="d_jx1ihmy"/><path class="y_uzo0aoe"/><path class="zxqj09xoy"/><path class="dxtjnbb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sbt" /></template>
<style>
.d_jx1ihmy {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--0e3a51, #0e3a51);
}

.dxtjnbb9h {
  fill: var(--svg-color--de3423, #de3423);
  d: path("M29.572 19.379H10.9a1.624 1.624 0 0 0 0 3.248h17.433a14 14 0 0 0 1.239-3.248");
}

.y_uzo0aoe {
  fill: var(--svg-color--15a9ce, #15a9ce);
  d: path("M12.64 15.72a1.625 1.625 0 0 0 1.624 1.624h15.668c.042-.444.068-.89.068-1.344a14 14 0 0 0-.144-1.9H14.264a1.625 1.625 0 0 0-1.624 1.62");
}

.zxqj09xoy {
  fill: var(--svg-color--92d13d, #92d13d);
  d: path("M17.624 8.795a1.624 1.624 0 1 0 0 3.248h11.8a14 14 0 0 0-1.437-3.248Z");
}

</style>
