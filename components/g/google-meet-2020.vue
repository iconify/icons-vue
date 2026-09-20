<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":211};
const content = `<path class="yxf03t7bw"/><path class="ja3kodbfb"/><path class="yvb7yf3df"/><path class="uu44m201n"/><path class="v3ayco-lp"/><path class="i-fibjbec"/><path class="aj5g-hbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-meet-2020" /></template>
<style>
.aj5g-hbdp {
  fill: var(--svg-color--ffba00, #ffba00);
  d: path("M185.788 0H59.984v59.984h84.838v45.338l58.52-48.49V17.555c0-9.69-7.864-17.554-17.554-17.554");
}

.i-fibjbec {
  fill: var(--svg-color--00ac47, #00ac47);
  d: path("M144.822 105.322v45.338H59.984v59.984h125.804c9.69 0 17.553-7.866 17.553-17.554v-37.796z");
}

.ja3kodbfb {
  fill: var(--svg-color--0066da, #0066da);
  d: path("M0 150.66v42.43c0 9.688 7.864 17.554 17.554 17.554h42.43l8.786-32.059l-8.786-27.925l-29.11-8.786z");
}

.uu44m201n {
  fill: var(--svg-color--2684fc, #2684fc);
  d: path("M.001 150.679h59.983V59.983H.001z");
}

.v3ayco-lp {
  fill: var(--svg-color--00ac47, #00ac47);
  d: path("M241.659 25.398L203.34 56.834v98.46l38.477 31.558c5.76 4.512 14.186.4 14.186-6.922V32.18c0-7.403-8.627-11.495-14.345-6.781");
}

.yvb7yf3df {
  fill: var(--svg-color--e94235, #e94235);
  d: path("M59.984 0L0 59.984l30.876 8.765l29.108-8.765l8.626-27.545z");
}

.yxf03t7bw {
  fill: var(--svg-color--00832d, #00832d);
  d: path("m144.822 105.322l24.957 28.527l33.562 21.445l5.838-49.792l-5.838-48.669l-34.205 18.839z");
}

</style>
