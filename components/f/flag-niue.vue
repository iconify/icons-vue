<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qcs-ymbyl"/><path class="xu6y3ywwp"/><path class="wl11_5bnu"/><path class="dszb4-zhg"/><path class="u1lr-s33f"/><circle class="lljl_d7ho"/><path class="osykhfoeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-niue" /></template>
<style>
.dszb4-zhg {
  fill: var(--svg-color--cf1b2b, #cf1b2b);
  d: path("M11 5H8v5H0v3h8v5h3v-5h8v-3h-8z");
}

.lljl_d7ho {
  cx: 9.5px;
  cy: 11.5px;
  r: 2.5px;
  fill: var(--svg-color--004a77, #004a77);
}

.osykhfoeh {
  fill: var(--svg-color--ffe150, #ffe150);
  d: path("m9.5 8.966l.599 1.6l1.824.038l-1.454 1.225l.529 1.746L9.5 12.533l-1.498 1.042l.529-1.746l-1.454-1.225l1.824-.038zm-5.676 1.519l.246.707l.748.016l-.596.452l.216.716l-.614-.427l-.614.427l.217-.716l-.597-.452l.749-.016zm11.352 0l.246.707l.748.016l-.596.452l.216.716l-.614-.427l-.614.427l.216-.716l-.596-.452l.748-.016zM9.5 5.821l.246.707l.748.016l-.596.452l.216.716l-.614-.427l-.614.427l.217-.716l-.597-.452l.748-.016zm0 9.467l.246.707l.748.015l-.596.452l.216.717l-.614-.428l-.614.428l.217-.717l-.597-.452l.748-.015z");
}

.qcs-ymbyl {
  fill: var(--svg-color--ffe150, #ffe150);
  d: path("M32 5H4q-.308 0-.604.045l-.004 1.754l-2.73-.004A4 4 0 0 0 0 9v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.u1lr-s33f {
  fill: var(--svg-color--cf1b2b, #cf1b2b);
  d: path("M19 5h-1.461L12 8.879V9h1.571L19 5.198zm-17.276.71a4 4 0 0 0-.757.681L4.69 9h1.735zM6.437 14L.734 18h1.727L7 14.822V14zM19 17.802v-1.22L15.313 14H13.57z");
}

.wl11_5bnu {
  fill: var(--svg-color--eee, #eee);
  d: path("M19 5h-2.331L12 8.269V5H7v2.569L3.396 5.045a3.94 3.94 0 0 0-1.672.665L6.426 9H4.69L.967 6.391a4 4 0 0 0-.305.404L3.813 9H0v5h3.885L0 16.766V18h3.332L7 15.432V18h5v-3.269L16.668 18H19v-2.029L16.185 14H19V9h-2.814L19 7.029z");
}

.xu6y3ywwp {
  fill: var(--svg-color--00247d, #00247d);
  d: path("M19 18V5H4c-.32 0-.604.045-.604.045l-.004 1.754l-2.73-.004S.62 6.854.535 7A4 4 0 0 0 0 9v9z");
}

</style>
