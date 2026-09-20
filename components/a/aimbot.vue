<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGoONCxbLi)" class="es7yom62i"/><path fill="url(#SVGQTi8kPSj)" class="tnhs9qpuj"/><path fill="url(#SVGxmM6dcaa)" class="pq2ubm3pi"/><defs><linearGradient id="SVGoONCxbLi" x1="1075.02" x2="923.259" y1="380.606" y2="635.94" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="zo5anjb9e"/></linearGradient><linearGradient id="SVGQTi8kPSj" x1="5959.19" x2="8216.67" y1="610.138" y2="7705.73" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/></linearGradient><linearGradient id="SVGxmM6dcaa" x1="36153.6" x2="36153.6" y1="609.778" y2="37794.1" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aimbot" /></template>
<style>
.es7yom62i {
  d: path("m7.95 11.843l4.032 1.957L16.05 12l-4.068-1.8");
}

.ft5dv1b6b {
  fill: none;
}

.pq2ubm3pi {
  d: path("M18.782 7.5H5.218L3 10.052v3.896L5.218 16.5h13.564L21 13.948v-3.896zm.112 6.03s-.729 1.17-1.107 1.17H6.213c-.378 0-1.107-1.17-1.107-1.17s-.077-.778-.077-1.521s.077-1.521.077-1.521L6.213 9.3h11.574l1.107 1.188s.077.779.077 1.52c0 .744-.077 1.522-.077 1.522");
}

.tnhs9qpuj {
  d: path("m7.95 11.843l4.032 1.957v-3.6z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.zo5anjb9e {
  stop-color: var(--svg-color--8f9196, #8f9196);
}

</style>
