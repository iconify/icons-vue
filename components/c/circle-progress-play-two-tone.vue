<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jefko1b_v"/><path class="hc5d41b9j"/><path class="a483nz4oq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-play-two-tone" /></template>
<style>
.a483nz4oq {
  d: path("M12 22C6.47715 22 2 17.5229 2 12C2 6.47715 6.47715 2 12 2M8.962734 9.105541C8.962734 8.320105 9.826684 7.841262 10.492732 8.257542L15.802266 11.576001C16.1156 11.771835 16.1156 12.228165 15.802266 12.423999L10.492732 15.742458C9.826684 16.158738 8.962734 15.679895 8.962734 14.894459Z");
}

.hc5d41b9j {
  stroke-opacity: 0.4;
  d: path("M17.8778 3.90983C18.7268 4.52663 19.4734 5.2732 20.0902 6.12215M21.8769 10.4357C22.041 11.4721 22.041 12.5279 21.8769 13.5643M20.0902 17.8778C19.4734 18.7268 18.7268 19.4734 17.8778 20.0902");
}

.jefko1b_v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.962734 9.105541C7.962734 7.53467 9.690636 6.576985 11.022732 7.409545L16.332265 10.728003C17.272267 11.315504 17.272267 12.684496 16.332265 13.271998L11.022732 16.590456C9.690636 17.423016 7.962734 16.465331 7.962734 14.89446Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
