<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yjy778bqm"/><path class="j7zmd-ffh"/><path class="gj4c32bgl"/><path class="p0kbhrtll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:hospital" /></template>
<style>
.gj4c32bgl {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M113.81 36.9H95.85c-2.03 0-3.84-.26-4.99-1.2c-1.12-.92-1.44-2.71-1.47-4.12v-18.4c0-5.45-4.46-9.9-9.9-9.9H48.5c-5.45 0-9.91 4.45-9.91 9.9v18.4c-.02 1.41-.35 3.2-1.46 4.12c-1.15.95-2.96 1.2-4.99 1.2H14.19c-5.46 0-9.91 4.45-9.91 9.91V128H47.4v-12.98c0-3.04 2.47-5.53 5.52-5.53h22.15c3.04 0 5.53 2.49 5.53 5.53V128h43.13V46.81c-.01-5.46-4.47-9.91-9.92-9.91M28.88 95.12H16.56v-15.7h12.32zm0-24.95H16.56v-15.7h12.32zm20.64 24.95H37.2v-15.7h12.32zm0-24.95H37.2v-15.7h12.32zm20.63 24.95H57.82v-15.7h12.33zm0-24.95H57.82v-15.7h12.33zm20.63 24.95H78.47v-15.7h12.31zm0-24.95H78.47v-15.7h12.31zm20.64 24.95H99.1v-15.7h12.32zm0-24.95H99.1v-15.7h12.32z");
}

.j7zmd-ffh {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M80.82 44.76V9.68H47.36v35.08H10.12v60.44H115.9V44.76z");
}

.p0kbhrtll {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M74.99 27.2c0 1.12-.91 2.04-2.03 2.04h-3.32c-1.12 0-2.04.92-2.04 2.04v3.32c0 1.12-.92 2.04-2.04 2.04h-3.12c-1.12 0-2.04-.92-2.04-2.04v-3.32c0-1.12-.92-2.04-2.04-2.04h-3.32c-1.12 0-2.04-.92-2.04-2.04v-3.12c0-1.12.92-2.04 2.04-2.04h3.32c1.12 0 2.04-.92 2.04-2.04v-3.32c0-1.12.92-2.04 2.04-2.04h3.12c1.12 0 2.04.92 2.04 2.04V20c0 1.12.92 2.04 2.04 2.04h3.32c1.12 0 2.03.92 2.03 2.04z");
}

.yjy778bqm {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M39.46 102.22h47.97V128H39.46z");
}

</style>
