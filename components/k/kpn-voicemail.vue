<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ktmvnvfmg"/><circle class="a9uw-0c0k"/><circle class="kc4botbkc"/><path class="wj3d1650z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kpn-voicemail" /></template>
<style>
.a9uw-0c0k {
  cx: 16px;
  cy: 24px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kc4botbkc {
  cx: 32px;
  cy: 24px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ktmvnvfmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.835 2.606c-10.078.985-18.229 9.135-19.227 19.211c-.442 4.47.492 8.688 2.422 12.296c.636 1.189.816 2.568.433 3.86l-.91 3.069c-.437 1.472.933 2.842 2.405 2.405l3.068-.91c1.293-.383 2.672-.203 3.861.433c3.608 1.93 7.826 2.864 12.295 2.422c10.077-.998 18.227-9.15 19.212-19.227C46.72 12.59 35.41 1.279 21.835 2.606");
}

.wj3d1650z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16 30h16");
}

</style>
