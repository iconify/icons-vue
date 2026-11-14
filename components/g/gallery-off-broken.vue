<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="weaezd-oj"/><path class="ue43fsb3n"/><path class="ftcspie5e"/><path class="b86rpkbpc"/><path class="hjgg1hbjv"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-off-broken" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.b86rpkbpc {
  d: path("M18 8C18 9.1046 17.1046 10 16 10C14.8954 10 14 9.1046 14 8C14 6.8954 14.8954 6 16 6C17.1046 6 18 6.8954 18 8Z");
}

.ftcspie5e {
  d: path("M22.0009 12.3545C22.0003 14.9805 21.9877 16.849 21.6895 18.2331");
}

.hjgg1hbjv {
  d: path("M2 12.5001L3.7516 10.9675C4.6629 10.1702 6.0363 10.2159 6.8925 11.0721L11.1822 15.3618C11.8694 16.0491 12.9512 16.1428 13.7464 15.5839L14.0446 15.3744C14.3247 15.1775 14.6291 15.0344 14.9443 14.9443");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ue43fsb3n {
  d: path("M5.76758 2.3113C7.21328 2 9.18718 2 12.0007 2C16.7147 2 19.0718 2 20.5362 3.4645C21.6442 4.5724 21.9139 6.1911 21.9796 8.9549");
}

.weaezd-oj {
  d: path("M20.5355 20.5358C19.0711 22.0003 16.714 22.0003 12 22.0003C7.2859 22.0003 4.9289 22.0003 3.4645 20.5358C2 19.0714 2 16.7143 2 12.0003C2 7.28624 2 4.92924 3.4645 3.46484");
}

</style>
