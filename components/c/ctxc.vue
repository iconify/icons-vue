<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGmB09jcPm)" class="erbs6t36d"/><path fill="url(#SVGA9y5UbtM)" class="a7x_vvdxu"/><path fill="url(#SVGfF96EcpJ)" class="f2yrv5bsn"/><defs><linearGradient id="SVGmB09jcPm" x1="2.996" x2="9.272" y1="4.126" y2="23.648" gradientUnits="userSpaceOnUse"><stop class="cga3zbn6n"/><stop offset="1" class="dl10_o4-g"/></linearGradient><linearGradient id="SVGA9y5UbtM" x1="18.486" x2="9.724" y1="7.6" y2="23.568" gradientUnits="userSpaceOnUse"><stop class="wimn8lb9p"/><stop offset="1" class="dl10_o4-g"/></linearGradient><linearGradient id="SVGfF96EcpJ" x1="3.72" x2="20.066" y1="19.875" y2="19.875" gradientUnits="userSpaceOnUse"><stop class="qkevm6kxh"/><stop offset=".47" class="hhjh8mosu"/><stop offset="1" class="lrd9h-gnm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctxc" /></template>
<style>
.a7x_vvdxu {
  d: path("M11.482 4.48a.6.6 0 0 1 .074.129c.888 2.565 1.8 5.13 2.683 7.695c.078.214-.22.394-.36.23c-.76-.804-1.48-1.63-2.222-2.44c-.118-.113-.293-.04-.371.078l-7.73 9.242c-.09.095-.168.242-.314.259c-.113 0-.18-.085-.242-.17v-.14c2.83-4.961 5.659-9.917 8.482-14.883");
}

.cga3zbn6n {
  stop-color: var(--svg-color--307cc0, #307cc0);
}

.dl10_o4-g {
  stop-color: var(--svg-color--58bfdc, #58bfdc);
}

.erbs6t36d {
  d: path("M11.916 4.458c-.118-.276.315-.473.433-.209l8.42 14.777c-.146 0-.292-.05-.433-.073l-7.498-1.519c-.242-.01-.298-.416-.056-.478l2.936-.821a.24.24 0 0 0 .169-.135a.25.25 0 0 0 0-.214L11.916 4.452z");
}

.f2yrv5bsn {
  d: path("M9.12 13.283c.146-.045.338.056.287.236c-.298 1.063-.619 2.12-.928 3.173c-.05.135.073.258.197.264c4.044.827 8.088 1.682 12.133 2.503c.079.011.13.073.191.124v.169l-.113.123H3.72c1.8-2.193 3.595-4.41 5.4-6.592");
}

.ft5dv1b6b {
  fill: none;
}

.hhjh8mosu {
  stop-color: var(--svg-color--dedfdf, #dedfdf);
}

.lrd9h-gnm {
  stop-color: var(--svg-color--b1b2b2, #b1b2b2);
}

.qkevm6kxh {
  stop-color: var(--svg-color--acadad, #acadad);
}

.wimn8lb9p {
  stop-color: var(--svg-color--388bc7, #388bc7);
}

</style>
