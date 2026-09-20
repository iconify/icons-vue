<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGxuZ1Vd8S" x1="-134.907" x2="-134.896" y1="204.572" y2="204.572" gradientTransform="matrix(1538 0 0 -961.25 207495 196661)" gradientUnits="userSpaceOnUse"><stop offset="0" class="d28uh2b9z"/><stop offset=".6" class="vr3x6tb5e"/><stop offset=".8" class="vr3x6tb5e"/><stop offset="1" class="d28uh2b9z"/></linearGradient><linearGradient id="SVGSywV0BWL" x1="-134.907" x2="-134.896" y1="203.781" y2="203.781" gradientTransform="matrix(1538 0 0 -961.25 207495 195892)" href="#SVGxuZ1Vd8S"/><linearGradient id="SVGpRg1QdBw" x1="-134.907" x2="-134.896" y1="205.363" y2="205.363" gradientTransform="matrix(1538 0 0 -961.25 207495 197430)" href="#SVGxuZ1Vd8S"/></defs><path class="v_ximusss"/><path fill="url(#SVGxuZ1Vd8S)" class="ccqfacm6b"/><path fill="url(#SVGSywV0BWL)" class="uesp-lb1e"/><path fill="url(#SVGpRg1QdBw)" class="exwey-bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-scala" /></template>
<style>
.ccqfacm6b {
  d: path("M7.384 14.923v6.462c0-.538 17.232-1.615 17.232-4.308v-6.462c0 2.692-17.232 3.769-17.232 4.308");
}

.d28uh2b9z {
  stop-color: var(--svg-color--e62d2a, #e62d2a);
}

.exwey-bvc {
  d: path("M7.384 23.538V30c0-.538 17.232-1.615 17.232-4.308v-6.461c0 2.692-17.232 3.769-17.232 4.308");
}

.uesp-lb1e {
  d: path("M7.384 6.308v6.462c0-.538 17.232-1.615 17.232-4.308V2c0 2.692-17.232 3.769-17.232 4.308");
}

.v_ximusss {
  fill: var(--svg-color--7f0c1d, #7f0c1d);
  d: path("M7.384 19.231v2.154c0 .363 7.833.971 12.937 2.154c2.465-.571 4.295-1.277 4.295-2.154v-2.154c0-.877-1.83-1.582-4.295-2.154c-5.1 1.183-12.937 1.791-12.937 2.154m0-8.616v2.154c0 .363 7.833.971 12.937 2.154c2.465-.571 4.295-1.277 4.295-2.154v-2.154c0-.877-1.83-1.582-4.295-2.154c-5.1 1.183-12.937 1.791-12.937 2.154");
}

.vr3x6tb5e {
  stop-color: var(--svg-color--df3f3d, #df3f3d);
}

</style>
