<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="y94jm1b4c"><path class="xqfpdhbyh"/><path class="ihf8d2bdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:copyright" /></template>
<style>
.ihf8d2bdy {
  d: path("M86.34 76.53a.88.88 0 0 0-.58-.45c-.26-.05-.52 0-.72.17c-4.57 3.62-12.42 6.35-18.26 6.35c-11.3 0-19.2-7.65-19.2-18.6s7.9-18.6 19.2-18.6c6.11 0 12.38 1.97 16.36 5.14c.2.16.46.22.71.17s.46-.21.59-.43l9.05-16.49c.21-.37.11-.83-.22-1.09c-6.84-5.42-15.54-8.06-26.57-8.06c-23.5 0-40.55 16.56-40.55 39.38S43.2 103.4 66.7 103.4c10.75 0 20.04-3.27 27.6-9.73c.3-.26.39-.69.21-1.05z");
}

.xqfpdhbyh {
  d: path("M64 .28C28.82.28.29 28.81.29 64S28.82 127.71 64 127.71c35.19 0 63.71-28.52 63.71-63.71S99.19.28 64 .28m0 121.33c-31.77 0-57.61-25.84-57.61-57.6C6.39 32.23 32.23 6.39 64 6.39S121.61 32.23 121.61 64S95.77 121.61 64 121.61");
}

.y94jm1b4c {
  fill: var(--svg-color--40c0e7, #40c0e7);
}

</style>
