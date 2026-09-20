<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yvx_n0-bv"/><path class="utrx-tb0k"/><path class="btm8q8b-e"/><path class="ic-e5_bvo"/><path class="b3pv9nbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-aspx" /></template>
<style>
.b3pv9nbnt {
  fill: var(--svg-color--33a9dc, #33a9dc);
  stroke: var(--svg-color--33a9dc, #33a9dc);
  stroke-miterlimit: 10;
  d: path("M8.536 29.055A25.44 25.44 0 0 1 8 10.608l.776.331a24.56 24.56 0 0 0 .533 17.783Zm7.064 0l-.776-.333a24.56 24.56 0 0 0 .531-17.783l.776-.331a25.44 25.44 0 0 1-.531 18.447ZM11.655 9.898h.889v20.371h-.889z");
}

.btm8q8b-e {
  fill: var(--svg-color--33a9dc, #33a9dc);
  d: path("M12.1 30.994A11.094 11.094 0 1 1 23.194 19.9A11.106 11.106 0 0 1 12.1 30.994m0-20.3a9.2 9.2 0 1 0 9.2 9.206a9.216 9.216 0 0 0-9.2-9.2Z");
}

.ic-e5_bvo {
  fill: var(--svg-color--33a9dc, #33a9dc);
  stroke: var(--svg-color--33a9dc, #33a9dc);
  stroke-miterlimit: 10;
  d: path("M2.099 19.455h20.003v.89H2.099zm10.226-3.692a32 32 0 0 1-8.484-1.11l.242-.807a31.4 31.4 0 0 0 15.992 0l.239.807a28 28 0 0 1-7.989 1.11ZM4.1 25.724l-.239-.807a31.65 31.65 0 0 1 16.472 0l-.242.807a31.4 31.4 0 0 0-15.991 0Z");
}

.utrx-tb0k {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M27.35 27.7H8.75V4.3h11.7v7h7v16.4z");
}

.yvx_n0-bv {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M22.75 2H6.35v28h23.3V9z");
}

</style>
