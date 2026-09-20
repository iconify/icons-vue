<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGqcZuTb5F" x1="22.748" x2="105.252" y1="64" y2="64" gradientUnits="userSpaceOnUse"><stop offset="0" class="rwhk7-m5g"/><stop offset="1" class="vlzxxcccm"/></linearGradient><path fill="url(#SVGqcZuTb5F)" class="ri7wl1bmt"/><path class="cee1ndpnv"/><path class="c7xdh4nrk"/><path class="vlceaobdi"/><path class="ud16_pd2d"/><path class="f-79hlyzm"/><path class="g5s9xdb2u"/><path class="ayywdw-rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:level-slider" /></template>
<style>
.ayywdw-rd {
  fill: var(--svg-color--455a64, #455a64);
  d: path("M59.4 43.63h-5.69c-1.85 0-2.57-2.39-1.03-3.42c.7-.47 1.67-.79 3-.79h9.41c.38 0 .53.49.21.7c-2.32 1.6-2.42 3.51-5.9 3.51");
}

.c7xdh4nrk {
  fill: var(--svg-color--212121, #212121);
  d: path("M64.07 115.19h-.14c-2.2 0-4-1.8-4-4V16.81c0-2.2 1.8-4 4-4h.14c2.2 0 4 1.8 4 4v94.37c0 2.21-1.8 4.01-4 4.01");
}

.cee1ndpnv {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M87.84 124H40.16c-7.41 0-13.47-6.06-13.47-13.47V17.47C26.68 10.06 32.75 4 40.16 4h47.69c7.41 0 13.47 6.06 13.47 13.47v93.05c0 7.42-6.07 13.48-13.48 13.48");
}

.f-79hlyzm {
  d: path("M76.33 53.49H57.47c-2.72 0-4.92-2.2-4.92-4.92v-2.12c0-2.72 2.2-4.92 4.92-4.92h18.86c2.72 0 4.92 2.2 4.92 4.92v2.12c0 2.71-2.2 4.92-4.92 4.92");
  opacity: var(--svg-opacity--0-26, 0.26);
}

.g5s9xdb2u {
  d: path("M73.33 50.41H54.47c-2.72 0-4.92-2.2-4.92-4.92v-2.12c0-2.72 2.2-4.92 4.92-4.92h18.86c2.72 0 4.92 2.2 4.92 4.92v2.12c0 2.72-2.2 4.92-4.92 4.92");
}

.ri7wl1bmt {
  d: path("M92.53 124H35.47c-7 0-12.72-5.72-12.72-12.72V16.72c0-7 5.72-12.72 12.72-12.72h57.06c7 0 12.72 5.72 12.72 12.72v94.56c0 7-5.72 12.72-12.72 12.72");
}

.rwhk7-m5g {
  stop-color: var(--svg-color--eee, #eee);
}

.ud16_pd2d {
  fill: none;
  stroke: var(--svg-color--424242, #424242);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M73.54 16.29H91.4m-17.86 9.54H91.4m-17.86 9.54H91.4m-17.86 9.55H91.4m-17.86 9.54H91.4M73.54 64H91.4m-17.86 9.54H91.4m-17.86 9.54H91.4m-17.86 9.55H91.4m-17.86 9.54H91.4m-17.86 9.54H91.4M36.6 16.29h17.86M36.6 25.83h17.86M36.6 35.37h17.86M36.6 44.92h17.86M36.6 54.46h17.86M36.6 64h17.86M36.6 73.54h17.86M36.6 83.08h17.86M36.6 92.63h17.86m-17.86 9.54h17.86m-17.86 9.54h17.86");
}

.vlceaobdi {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M64 12.81c-.42 0-.82.08-1.21.2c1.65.5 2.86 1.98 2.86 3.74v94.5c0 1.76-1.21 3.24-2.86 3.74c.38.12.78.2 1.21.2c2.24 0 4.07-1.77 4.07-3.94v-94.5c0-2.16-1.83-3.94-4.07-3.94");
}

.vlzxxcccm {
  stop-color: var(--svg-color--757575, #757575);
}

</style>
