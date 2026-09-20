<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bmhr73u2p"/><path class="ux93bflxd"/><path class="nkssc8bqz"/><circle class="pt2im-bis"/><path class="stldrvbfg"/><path class="pzgitcbwo"/><path class="w0dz0817m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-grenada" /></template>
<style>
.bmhr73u2p {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.nkssc8bqz {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M3.5 8.5h29l-29 19h29z");
}

.pt2im-bis {
  cx: 18px;
  cy: 18px;
  r: 3.5px;
  fill: var(--svg-color--ce1126, #ce1126);
}

.pzgitcbwo {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M6.118 19.067c.304.315.645.579.962.712a4.3 4.3 0 0 0-.164-1.148c-.268-.251-.572-.464-.868-.577c-.043.318-.012.673.07 1.013");
}

.stldrvbfg {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("m18 14.798l.719 2.213h2.326l-1.882 1.367l.719 2.212L18 19.223l-1.882 1.367l.719-2.212l-1.882-1.367h2.326zm0-9.616l.386 1.188h1.249l-1.01.734l.386 1.188L18 7.558l-1.011.734l.386-1.188l-1.01-.734h1.249zm8.02 0l.386 1.188h1.249l-1.01.734l.386 1.188l-1.011-.734l-1.01.734l.386-1.188l-1.011-.734h1.249zm-16.04 0l.386 1.188h1.249l-1.011.734l.386 1.188l-1.01-.734l-1.011.734l.386-1.188l-1.01-.734h1.249zm8.02 22.5l.386 1.188h1.249l-1.01.734l.386 1.188L18 30.058l-1.011.734l.386-1.188l-1.01-.734h1.249zm8.02 0l.386 1.188h1.249l-1.01.734l.386 1.188l-1.011-.734l-1.01.734l.386-1.188l-1.011-.734h1.249zm-16.04 0l.386 1.188h1.249l-1.011.734l.386 1.188l-1.01-.734l-1.011.734l.386-1.188l-1.01-.734h1.249z");
}

.ux93bflxd {
  fill: var(--svg-color--007a5e, #007a5e);
  d: path("M3.5 8.5h29v19h-29z");
}

.w0dz0817m {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M7.643 19.563c.803-2.916-2.06-2.738-2.803-3.67c.512 1.068-1.329 3.617 1.739 4.214a3 3 0 0 1-.46-1.04a2.8 2.8 0 0 1-.07-1.013c.297.113.6.326.868.577c.313.293.578.637.726.932");
}

</style>
