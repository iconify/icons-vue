<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kuak_ubat"/><path clip-rule="evenodd" class="wdp0_lb_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-to-line-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kuak_ubat {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.1761 4.287C12.57 3.9 13.204 3.905 13.5911 4.299C13.978 4.693 13.9721 5.326 13.5784 5.713L8.1985 11H22.0003C22.5526 11 23.0003 11.448 23.0003 12C23.0003 12.552 22.5526 13 22.0003 13H8.1985L13.5784 18.287C13.9721 18.674 13.978 19.307 13.5911 19.701C13.204 20.095 12.57 20.1 12.1761 19.713L5.473 13.126C4.8423 12.506 4.8423 11.494 5.473 10.874L12.1761 4.287Z");
}

.wdp0_lb_t {
  fill-rule: evenodd;
  d: path("M1 19V5C1 4.448 1.4477 4 2 4C2.5523 4 3 4.448 3 5V19C3 19.552 2.5523 20 2 20C1.4477 20 1 19.552 1 19Z");
}

</style>
