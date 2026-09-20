<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<defs><linearGradient id="SVGn2MHwese" x2="1" y1="500.019" y2="500.019" gradientTransform="rotate(-74.61 -56582.086 43258.207)scale(-173.67 173.67)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1"/></linearGradient><linearGradient id="SVGVbV6qbuh" x2="1" y1="500.066" y2="500.066" gradientTransform="matrix(136.419 107.5 107.5 -136.419 -53573.749 68567.906)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1" class="d9ofppbqf"/></linearGradient></defs><path class="qh3zo5b9y"/><path class="xp_t88bbs"/><path class="cskfjibci"/><path class="uphsg3b2c"/><path class="ksbqr1t8z"/><path fill="url(#SVGn2MHwese)" class="x3x-yvb5g"/><path class="mpde6ubvh"/><path class="o5otz7bts"/><path fill="url(#SVGVbV6qbuh)" class="vz2podbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cypress-opened" /></template>
<style>
.cskfjibci {
  d: path("M307.469 156.641c85.984-3.063 158.312 64.3 161.406 150.328a155.9 155.9 0 0 1-150.188 161.39c-85.984 3.062-158.312-64.3-161.406-150.328c-3.094-86.016 64.2-158.344 150.188-161.391Z");
}

.cxqk8zbds {
  stop-color: var(--svg-color--58d09e, #58d09e);
}

.d9ofppbqf {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
}

.ksbqr1t8z {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M267.656 281.672c12.266 0 22.266 6.484 27.391 17.812l.406.875l20.609-6.938l-.453-1.047c-7.969-19.266-26.344-31.25-47.953-31.25c-15.188 0-27.531 4.844-37.734 14.75c-10.141 9.859-15.266 22.25-15.266 36.844c0 14.484 5.125 26.812 15.266 36.656c10.2 9.922 22.547 14.75 37.734 14.75c21.609 0 39.984-11.984 47.953-31.234l.453-1.047l-20.641-6.953l-.391.922c-4.594 11.125-14.828 17.766-27.375 17.766a28.93 28.93 0 0 1-21.469-8.8a30.4 30.4 0 0 1-8.7-22.047a30.86 30.86 0 0 1 8.7-22.234a28.87 28.87 0 0 1 21.47-8.825");
}

.mpde6ubvh {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M167.172 352.188a149 149 0 0 1-5.391-39.828c0-61.641 39.031-118.016 97.141-140.25l7.625 19.562c-50.016 19.141-83.609 67.641-83.609 120.687a128.2 128.2 0 0 0 4.625 34.266z");
}

.o5otz7bts {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M257.906 172.594a153.2 153.2 0 0 1 39.375-9.484c61.812-6.437 122.422 26.172 150.781 81.172l-18.813 9.562c-24.422-47.344-76.562-75.406-129.766-69.859a131 131 0 0 0-33.875 8.141l-7.7-19.531Z");
}

.qh3zo5b9y {
  fill: var(--svg-color--2c9a6a, #2c9a6a);
  d: path("M460.938 85.938H284.375l-32.813 65.625H67.188v262.5h393.75Zm-32.813 292.187h-325v-193.75h325Zm0-226.562H300l15.625-32.812h110.938v32.812z");
}

.uphsg3b2c {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M396.672 263.031L367.328 336.7l-29.547-73.672h-24.187l41.453 100.563l-29.484 70.922l21.125 4.172l72.828-175.656h-22.844Z");
}

.vz2podbno {
  d: path("m329.656 424.578l-5.141 12.375a6.85 6.85 0 0 1-6 4.2a117 117 0 0 1-5.266.125c-60.609-.031-114.234-42.422-127.516-100.812l-20.625 4.625a150.57 150.57 0 0 0 52.692 83.721a153.24 153.24 0 0 0 95.234 33.422h.313c2.031 0 4.047-.047 6.063-.125a28.07 28.07 0 0 0 24.687-17.188l6.719-16.172l-21.156-4.172Z");
}

.x3x-yvb5g {
  d: path("M382.734 421.672a129.45 129.45 0 0 0 45.75-169.516l18.734-9.687a150.205 150.205 0 0 1-53.125 196.891z");
}

.xp_t88bbs {
  fill: var(--svg-color--2c9a6a, #2c9a6a);
  d: path("M401.563 214.062H7.813l59.375 200h393.75Z");
}

</style>
