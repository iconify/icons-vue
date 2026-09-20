<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGZXgnfeoC" x1="17.649" x2="28.104" y1="8.845" y2="19.301" gradientUnits="userSpaceOnUse"><stop offset="0" class="aw-t_bg-j"/><stop offset="1" class="z8bgr0bko"/></linearGradient><linearGradient id="SVGkMfE6b4n" x1="10.011" x2="20.363" y1="22.109" y2="11.758" gradientTransform="matrix(1 0 0 -1 0 32.257)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h2odc0bvt"/><stop offset="1" class="jxpbwgawm"/></linearGradient><linearGradient id="SVGfAyvneeC" x1="-.155" x2="10.301" y1="8.846" y2="19.301" href="#SVGZXgnfeoC"/></defs><path fill="url(#SVGZXgnfeoC)" class="korei4vqs"/><path fill="url(#SVGkMfE6b4n)" class="b-k7tebgt"/><path fill="url(#SVGfAyvneeC)" class="vh7l1kg7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-pip" /></template>
<style>
.aw-t_bg-j {
  stop-color: var(--svg-color--387eb8, #387eb8);
}

.b-k7tebgt {
  d: path("M16.01 24.073h-.017c-2.561 0-2.561-3.585-2.561-3.585v-8.78s-.007-3.531 2.561-3.524h.018c2.51 0 2.51 3.524 2.51 3.524v8.78s0 3.584-2.511 3.585m.947-2.3a.914.914 0 1 0-.89.937l-.024-.007a.914.914 0 0 0 .914-.914Z");
}

.h2odc0bvt {
  stop-color: var(--svg-color--ffe052, #ffe052);
}

.jxpbwgawm {
  stop-color: var(--svg-color--ffc331, #ffc331);
}

.korei4vqs {
  d: path("m24.989 7.936l-.028-.009c-5.58 0-5.15 2.794-5.15 2.794v10.605s-.006 2.749 2.562 2.749h.018c2.513 0 2.51-2.747 2.51-2.747V16.52h2.972C30 16.52 30 15.159 30 15.159v-4.913s.333-2.31-5.011-2.31m3.7 2.541a.914.914 0 1 1-.89-.936l-.024.007a.914.914 0 0 1 .914.914z");
}

.vh7l1kg7z {
  d: path("m7.186 7.936l-.028-.012c-5.58 0-5.15 2.794-5.15 2.794v10.608s-.008 2.75 2.56 2.75h.018c2.513 0 2.51-2.747 2.51-2.747V16.52h2.971c2.129 0 2.124-1.361 2.124-1.361v-4.913s.335-2.31-5.005-2.31m3.7 2.541A.914.914 0 1 1 10 9.54l-.024.007a.914.914 0 0 1 .914.914v.015Z");
}

.z8bgr0bko {
  stop-color: var(--svg-color--366994, #366994);
}

</style>
