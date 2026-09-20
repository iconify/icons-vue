<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="wdn0sobtb"/><path class="ozeftcczu"/><path class="qwpu2qb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:lying-face" /></template>
<style>
.ozeftcczu {
  fill: var(--svg-color--664500, #664500);
  d: path("M11.471 13.529c0 1.706-.987 3.088-2.206 3.088s-2.206-1.382-2.206-3.088c0-1.705.987-3.088 2.206-3.088s2.206 1.383 2.206 3.088m11.529 0c0 1.706-.987 3.088-2.206 3.088s-2.206-1.382-2.206-3.088c0-1.705.988-3.088 2.206-3.088c1.219 0 2.206 1.383 2.206 3.088M10.118 29.382c1.765-4.412 11.471-4.412 11.471-2.647c-.001.883-7.06-.882-11.471 2.647");
}

.qwpu2qb_c {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M32.262 17.5H17c-1.511 0-2.734 1.344-2.734 3c0 1.657 1.224 3 2.734 3h15.262c1.513 0 2.738-1.343 2.738-3c0-1.656-1.226-3-2.738-3");
}

.wdn0sobtb {
  cx: 16px;
  cy: 18px;
  r: 16px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

</style>
