<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG0HJh4crz" x1="-133.268" x2="-133.198" y1="-202.91" y2="-202.84" gradientTransform="matrix(189.38 0 0 189.81 25243.061 38519.17)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cbpgs4yfj"/><stop offset="1" class="oz5z72brq"/></linearGradient><linearGradient id="SVGklWpvehB" x1="-133.575" x2="-133.495" y1="-203.203" y2="-203.133" gradientTransform="matrix(189.38 0 0 189.81 25309.061 38583.42)" gradientUnits="userSpaceOnUse"><stop offset="0" class="b8rop1bve"/><stop offset="1" class="prefjfggu"/></linearGradient></defs><path fill="url(#SVG0HJh4crz)" class="dztrm4yuu"/><path fill="url(#SVGklWpvehB)" class="c1i5y8jgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-pyenv" /></template>
<style>
.b8rop1bve {
  stop-color: var(--svg-color--dadada, #dadada);
}

.c1i5y8jgw {
  d: path("M16.085 29.91c7.1 0 6.651-3.08 6.651-3.08v-3.18h-6.751v-1h9.47S30 23.158 30 15.995s-4.013-6.912-4.013-6.912H23.64V12.4s.13 4.013-3.9 4.013h-6.765S9.2 16.356 9.2 20.068V26.2s-.572 3.712 6.842 3.712h.04Zm3.732-2.147A1.214 1.214 0 1 1 21 26.519v.03a1.214 1.214 0 0 1-1.214 1.214z");
}

.cbpgs4yfj {
  stop-color: var(--svg-color--6f6f6f, #6f6f6f);
}

.dztrm4yuu {
  d: path("M15.885 2.1c-7.1 0-6.651 3.07-6.651 3.07v3.19h6.752v1H6.545S2 8.8 2 16.005s4.013 6.912 4.013 6.912H8.33v-3.361s-.13-4.013 3.9-4.013h6.762s3.772.06 3.772-3.652V5.8s.572-3.712-6.842-3.712Zm-3.732 2.137a1.214 1.214 0 1 1-1.183 1.244v-.02a1.214 1.214 0 0 1 1.214-1.214Z");
}

.oz5z72brq {
  stop-color: var(--svg-color--5e5e5e, #5e5e5e);
}

.prefjfggu {
  stop-color: var(--svg-color--c5c5c5, #c5c5c5);
}

</style>
