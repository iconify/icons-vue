<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9Xheddwr)" class="r4i437pya"/><path class="fi73s1cik"/></g><defs><linearGradient id="SVG9Xheddwr" x1="4" x2="16.138" y1="6.767" y2="20.001" gradientUnits="userSpaceOnUse"><stop class="tbiy8ey5h"/><stop offset=".11" class="odpv4lbce"/><stop offset=".47" class="lukkp90wc"/><stop offset="1" class="asgldebtu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hilo-background" /></template>
<style>
.asgldebtu {
  stop-color: var(--svg-color--c772ad, #c772ad);
}

.fi73s1cik {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.069 5.807a8.03 8.03 0 0 1 2.93 6.275l-.075.908a8 8 0 0 1-7.625 7.005a8.11 8.11 0 0 1-7.62-4.766a8.01 8.01 0 0 1 6.477-11.19q3.336-.298 5.918 1.768zm-12.09 6.275q-.001.704.146 1.416a7.13 7.13 0 0 0 6.939 5.533a7.12 7.12 0 0 0 6.962-6.949A7.11 7.11 0 0 0 12.04 4.96c-3.857-.028-7.103 3.246-7.065 7.122zm7.894-3.603c.113.075.221.16.315.259l2.08 2.14l.009.01c.2.178.366.392.489.63l-.005.005h-1.11a.06.06 0 0 1-.047-.02l-.174-.183l-1.176-1.213c-.155-.15-.306-.31-.461-.47c-.339-.354-.612-.612-1.068-.415c-.113.047-.24.146-.39.301L9.42 11.5a.06.06 0 0 1-.047.019l-.155.01h-.941l-.019-.005a.03.03 0 0 1-.014-.026q0-.01.005-.017q.1-.167.23-.31q1.043-1.1 2.108-2.192c.263-.269.46-.447.597-.518a1.66 1.66 0 0 1 1.694.019zm-3.528 3.99H8.263q-.006 0-.01.002l-.01.007l-.002.011q0 .006.003.012c.127.25.339.461.532.659l.028.023l1.707 1.76q.32.353.715.616q.707.393 1.548.019c.155-.095.282-.184.367-.273q1.187-1.222 2.37-2.446a1.6 1.6 0 0 0 .255-.363a.03.03 0 0 0-.014-.023h-1.087a.12.12 0 0 0-.094.037l-1.538 1.586l-.094.103c-.188.212-.424.48-.635.57c-.306.131-.626.046-.866-.193l-.673-.697l-1.336-1.378a.12.12 0 0 0-.089-.038z");
}

.ft5dv1b6b {
  fill: none;
}

.lukkp90wc {
  stop-color: var(--svg-color--3d065d, #3d065d);
}

.odpv4lbce {
  stop-color: var(--svg-color--4a53c4, #4a53c4);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tbiy8ey5h {
  stop-color: var(--svg-color--4a5dcd, #4a5dcd);
}

</style>
