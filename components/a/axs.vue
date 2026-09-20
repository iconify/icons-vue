<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGjL33xeCj)" class="yjuzgvmit"/><path fill="url(#SVG3I75OdTl)" class="yjuzgvmit"/><defs><linearGradient id="SVGjL33xeCj" x1="12" x2="12" y1="5.648" y2="18.352" gradientUnits="userSpaceOnUse"><stop class="fza6mobwn"/><stop offset="1" class="x10ubcctn"/></linearGradient><linearGradient id="SVG3I75OdTl" x1="21" x2="3" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="h_mt3wjeq"/><stop offset=".48" class="m2wqbey1h"/><stop offset="1" class="n__480oyl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:axs" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fza6mobwn {
  stop-color: var(--svg-color--00d2f7, #00d2f7);
}

.h_mt3wjeq {
  stop-color: var(--svg-color--8476f4, #8476f4);
}

.m2wqbey1h {
  stop-color: var(--svg-color--0083ec, #0083ec);
  stop-opacity: 0;
}

.n__480oyl {
  stop-color: var(--svg-color--8763ef, #8763ef);
}

.x10ubcctn {
  stop-color: var(--svg-color--004cdc, #004cdc);
}

.yjuzgvmit {
  d: path("M3.677 6.509c.615-.79 5.205 1.72 7.54 3.891a.26.26 0 0 1-.016.392l-.741.62a.266.266 0 0 1-.323.01l-1.525-1.096l-1.821 1.938c-.18.185-.503.577-.726.418a1.01 1.01 0 0 1-.275-1.138c.286-.662 1.805-2.05 1.805-2.05c-.762-.608-2.33-1.18-2.605.758c-.18 1.26-.137 6.433 2.065 5.189c2.118-1.202 10.563-10.558 12.252-9.743c1.69.81 2.277 9.743 1.011 11.363c-.413.53-3.166.19-7.545-3.505a.27.27 0 0 1-.074-.296a.3.3 0 0 1 .059-.09l.74-.726a.27.27 0 0 1 .372-.006c.995.869 4.622 3.654 5.014 1.785c.259-1.25.285-6.793-.98-6.385c-.688.222-1.906 1.207-2.817 1.985c-1.975 1.694-8.948 9.356-10.568 8.456c-1.62-.895-2.012-10.272-.847-11.77z");
}

</style>
