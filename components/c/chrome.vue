<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zyqy9zj1x"/><path class="vihqf6bpp"/><path class="sb1cwpqhi"/><path class="xyqnfjbji"/><path class="r52eyvbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:chrome" /></template>
<style>
.r52eyvbdo {
  fill: var(--svg-color--e33b2e, #e33b2e);
  d: path("M128.003 64.004H238.84a127.973 127.973 0 0 0-221.685.015l55.419 95.99l.015.008a63.993 63.993 0 0 1 55.415-96.014z");
}

.sb1cwpqhi {
  fill: var(--svg-color--fbc116, #fbc116);
  d: path("M128.008 255.996A127.97 127.97 0 0 0 256 127.997A128 128 0 0 0 238.837 64q-36.372-3.585-53.686-3.585q-19.632 0-57.152 3.585l-.014.01a63.99 63.99 0 0 1 55.444 31.987a63.99 63.99 0 0 1-.001 64.01z");
}

.vihqf6bpp {
  fill: var(--svg-color--229342, #229342);
  d: path("M35.89 92.997Q27.92 79.192 17.154 64.02a127.98 127.98 0 0 0 110.857 191.981q17.671-24.785 23.996-35.74q12.148-21.042 31.423-60.251v-.015a63.993 63.993 0 0 1-110.857.017Q46.395 111.19 35.89 92.998");
}

.xyqnfjbji {
  fill: var(--svg-color--1a73e8, #1a73e8);
  d: path("M128.003 178.677c27.984 0 50.669-22.685 50.669-50.67s-22.685-50.67-50.67-50.67c-27.983 0-50.669 22.686-50.669 50.67s22.686 50.67 50.67 50.67");
}

.zyqy9zj1x {
  fill: var(--svg-color--fff, #fff);
  d: path("M128.003 199.216c39.335 0 71.221-31.888 71.221-71.223S167.338 56.77 128.003 56.77S56.78 88.658 56.78 127.993s31.887 71.223 71.222 71.223");
}

</style>
