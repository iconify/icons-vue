<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGwMAivdcm)" class="b1xtzb4fi"/><defs><linearGradient id="SVGwMAivdcm" x1="19.801" x2="4.967" y1="6.054" y2="18.348" gradientUnits="userSpaceOnUse"><stop class="mvv2i2b7u"/><stop offset="1" class="rvt77lvmf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:divi" /></template>
<style>
.b1xtzb4fi {
  d: path("M12.858 3H3c1.254 2.91 2.892 4.2 4.926 4.2h4.698c1.878 0 3.99 2.376 3.99 4.8s-2.112 4.8-3.99 4.8H9v-5.364H4.686V21h8.172C16.848 21 21 18.066 21 12s-4.152-9-8.142-9");
}

.ft5dv1b6b {
  fill: none;
}

.mvv2i2b7u {
  stop-color: var(--svg-color--ec1f55, #ec1f55);
}

.rvt77lvmf {
  stop-color: var(--svg-color--ec2928, #ec2928);
}

</style>
