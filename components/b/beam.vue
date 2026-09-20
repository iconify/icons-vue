<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zw244_b6l"/><path class="p1vgzybyc"/><path class="uvmndxbvj"/><path class="eb89vab3x"/><path fill="url(#SVGVLHYUcWO)" class="sq8ibd9nx"/><path fill="url(#SVGngMHqeof)" class="esqq0_5qu"/><path fill="url(#SVGaSqFTd7x)" class="wf9ce_pfz"/><path fill="url(#SVGucLklqaz)" class="f_2l4bcyf"/><defs><linearGradient id="SVGVLHYUcWO" x1="3.009" x2="12.865" y1="12.032" y2="12.032" gradientUnits="userSpaceOnUse"><stop class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGngMHqeof" x1="20.892" x2="9.447" y1="11.974" y2="11.974" gradientUnits="userSpaceOnUse"><stop class="xgmqtuyjk"/><stop offset="1" class="prf8b7qvd"/></linearGradient><linearGradient id="SVGaSqFTd7x" x1="21.081" x2="11.811" y1="12.025" y2="12.025" gradientUnits="userSpaceOnUse"><stop class="c8larcb6p"/><stop offset="1" class="bx5bpmbpi"/></linearGradient><linearGradient id="SVGucLklqaz" x1="20.991" x2="15.69" y1="12.139" y2="12.139" gradientUnits="userSpaceOnUse"><stop class="lt77tib1y"/><stop offset="1" class="wvrkw6ybd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:beam" /></template>
<style>
.bx5bpmbpi {
  stop-color: var(--svg-color--a18cff, #a18cff);
}

.c8larcb6p {
  stop-color: var(--svg-color--9d6eff, #9d6eff);
  stop-opacity: 0;
}

.eb89vab3x {
  fill: var(--svg-color--00e2c2, #00e2c2);
  d: path("M12 11.55v3.6h2.25z");
}

.esqq0_5qu {
  d: path("m21 8.432l-9.009 5.373v.148l9.01-3.784z");
}

.f_2l4bcyf {
  d: path("m21 10.168l-9.009 3.78v.149l9.01-2.196z");
}

.ft5dv1b6b {
  fill: none;
}

.lt77tib1y {
  stop-color: var(--svg-color--ae60d6, #ae60d6);
  stop-opacity: 0;
}

.p1vgzybyc {
  fill: var(--svg-color--24c1ff, #24c1ff);
  d: path("M12 16.05H8.247L12 9.75V5.7L4.35 18.3H12z");
}

.prf8b7qvd {
  stop-color: var(--svg-color--ff51ff, #ff51ff);
}

.sq8ibd9nx {
  d: path("m3 9.643l8.99 4.158v.436L3 12.271z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.uvmndxbvj {
  fill: var(--svg-color--39fff2, #39fff2);
  d: path("M12 11.55v3.6H9.75z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wf9ce_pfz {
  d: path("m21 13.639l-9.009.603v-.144l9.01-2.196z");
}

.wvrkw6ybd {
  stop-color: var(--svg-color--ab38e6, #ab38e6);
}

.xgmqtuyjk {
  stop-color: var(--svg-color--fd76fd, #fd76fd);
  stop-opacity: 0;
}

.zw244_b6l {
  fill: var(--svg-color--0b76ff, #0b76ff);
  d: path("M12 16.05h3.735L12 9.75V5.7l7.65 12.6H12z");
}

</style>
