<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGSXlPzeWt)" class="xtn-r9jyb"/><path fill="url(#SVG2IKOOdYJ)" clip-rule="evenodd" class="qplfb_y-j"/><defs><linearGradient id="SVGSXlPzeWt" x1="3.867" x2="21.945" y1="19.5" y2="15.629" gradientUnits="userSpaceOnUse"><stop class="x3vl0hzwo"/><stop offset=".5" class="jr4dmxbnd"/><stop offset=".88" class="tvgoomo5u"/></linearGradient><linearGradient id="SVG2IKOOdYJ" x1="17.966" x2="4.8" y1="6.351" y2="16.807" gradientUnits="userSpaceOnUse"><stop class="fkui-l26v"/><stop offset="1" class="h-ve5pble"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dvf" /></template>
<style>
.fkui-l26v {
  stop-color: var(--svg-color--6fc3ce, #6fc3ce);
}

.ft5dv1b6b {
  fill: none;
}

.h-ve5pble {
  stop-color: var(--svg-color--f96962, #f96962);
}

.jr4dmxbnd {
  stop-color: var(--svg-color--ed5f5e, #ed5f5e);
}

.qplfb_y-j {
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-.53a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94");
}

.tvgoomo5u {
  stop-color: var(--svg-color--67c9cb, #67c9cb);
}

.x3vl0hzwo {
  stop-color: var(--svg-color--fcdea0, #fcdea0);
}

.xtn-r9jyb {
  d: path("M6.23 12.185c-.763-.095-1.054-.307-1.102-.397c-.069.842.233 2.52 1.975 2.52c1.736 0 2.234-1.408 2.266-2.117h.11c.16.275.144.63.112.767a2.37 2.37 0 0 1 1.705 2.219h.794c0-1.43-.53-2.25-.794-2.467l.08-.149c.423.226.758.588.952 1.027l.143.053c1.101.492 1.927.143 2.208-.095a2.1 2.1 0 0 1-.292-.884h.217c.011.063.106.317.413.847c.27.47.768.566 1.255.662c.196.037.392.074.567.132c.487.175.508.656.46.874h.524v-.424c0-.477-.275-.884-.53-1.255c-.216-.317-.423-.609-.423-.9c0-.513.286-.895.424-1.022c-.122-.037-.223-.18-.344-.354c-.18-.26-.408-.593-.863-.741a1.7 1.7 0 0 0-.688-.085c-.233.005-.562.016-1.202-.053c-.593-.069-.953-.37-1.34-.688c-.476-.408-.99-.832-2.011-.832c-1.467 0-1.96 1.234-2.028 1.853a1.24 1.24 0 0 0-.667-.524c.005.657-.148 1.461-.794 1.732c-.53.222-.969-.149-1.128-.36c-.206.222-.085.529 0 .661m3.97 2.992a2.64 2.64 0 0 0-.095-1.462l.1-.053c.572.434.657 1.207.625 1.515zm4.632-1.393c.1.138.424.445.9.572a1.8 1.8 0 0 1-.423.82h-.747c.19-.211.482-.804.148-1.265z");
}

</style>
