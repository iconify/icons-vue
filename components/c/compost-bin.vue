<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu7ghbbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:compost-bin" /></template>
<style>
.iu7ghbbhl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.272 9.25q.35-5.668 6.122-6.492q.148-.022.292.015q.145.037.264.127t.195.218t.097.276q.008.053.008.106q0 3.911-2.32 5.75h1.866l8.324-4.896q.128-.076.276-.097q.148-.02.292.017q.145.037.264.127t.194.219q.038.063.062.133q.025.07.035.143t.006.147t-.023.145q-.019.072-.051.138t-.076.126q-.045.059-.1.108t-.119.086L14.754 9.25h2.038q1.019 0 1.691.766q.671.765.54 1.775l-1.109 8.5q-.256 1.958-2.231 1.959H6.317q-1.975-.001-2.231-1.959l-1.109-8.5q-.131-1.01.54-1.775q.672-.766 1.691-.766z");
}

</style>
