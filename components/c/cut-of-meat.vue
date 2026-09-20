<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vbe44sbah"/><path class="cyt7zqb1i"/><path class="m-9lxlb2s"/><path class="uf2ybx4ge"/><path class="q2bcqpbeb"/><path class="dz7mboq8m"/><path class="tmmm0p7pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cut-of-meat" /></template>
<style>
.cyt7zqb1i {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M33 18h2v4h-2zM1 16h2v4H1z");
}

.dz7mboq8m {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M25 13.923c0 1.529-1.791 2.769-4 2.769s-4-1.24-4-2.769s1.791-2.769 4-2.769s4 1.24 4 2.769");
}

.m-9lxlb2s {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M30 24.308c-2.271 0-3.282-.755-4.455-1.628c-1.069-.797-2.281-1.699-4.458-1.831a6 6 0 0 0-.36-.011c-1.433 0-2.978.483-4.613.996c-1.712.535-3.482 1.089-5.113 1.089c-5.215 0-9-2.912-9-6.923c0-5.396 8.244-8.308 16-8.308c9.271 0 16 4.367 16 10.385C34 22.648 31.607 24.308 30 24.308");
}

.q2bcqpbeb {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M16.161 8.443S19 8.385 21 9.769c1 .692.335 2.25.335 2.25l1.665.52s-.062-.835 3-1.385c2.251-.404 4.542 1.385 4.542 1.385S28 9.077 23 8.385c-5-.693-6.839.058-6.839.058");
}

.tmmm0p7pm {
  fill: var(--svg-color--a7a9ac, #a7a9ac);
  d: path("M23 13.923c0 .765-.896 1.385-2 1.385s-2-.62-2-1.385s.896-1.384 2-1.384s2 .619 2 1.384");
}

.uf2ybx4ge {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M18 8.385c8.691 0 15 4.076 15 9.692c0 4.144-2.06 5.538-3 5.538c-1.834 0-2.585-.559-3.723-1.407c-1.133-.844-2.543-1.895-5.104-2.049a7 7 0 0 0-.446-.014c-1.648 0-3.289.514-5.025 1.057c-1.616.506-3.286 1.028-4.702 1.028c-3.976 0-8-2.141-8-6.23c0-4.946 7.729-7.615 15-7.615M18 7C9 7 1 10.461 1 16c0 4.154 4 7.615 10 7.615c3.454 0 7.111-2.085 9.727-2.085q.14 0 .273.008c3.909.235 4 3.462 9 3.462c2.341 0 5-2.077 5-6.923C35 11.846 28 7 18 7");
}

.vbe44sbah {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M18 11c-9 0-17 3.461-17 9c0 4.154 4 7.615 10 7.615c3.454 0 7.111-2.085 9.727-2.085q.14 0 .273.008c3.909.235 4 3.462 9 3.462c2.341 0 5-2.077 5-6.923C35 15.846 28 11 18 11");
}

</style>
