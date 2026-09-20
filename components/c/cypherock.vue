<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGlext1c5j)" class="sqdkv5bpv"/><path fill="url(#SVGs4kxThxH)" class="c7m9ymbpu"/><defs><linearGradient id="SVGlext1c5j" x1="4.137" x2="19.855" y1="16.748" y2="16.748" gradientUnits="userSpaceOnUse"><stop class="rdy3q2ast"/><stop offset=".006" class="rdy3q2ast"/><stop offset=".253" class="fdp62_bdt"/><stop offset=".298" class="uemnp80iw"/><stop offset=".388" class="o8apaqw0p"/><stop offset=".512" class="rl-9wvb2v"/><stop offset=".596" class="tq27dw91a"/><stop offset=".823" class="axfbzr3yy"/><stop offset=".871" class="bwvp5bbhr"/><stop offset="1" class="fdp62_bdt"/></linearGradient><linearGradient id="SVGs4kxThxH" x1="4.137" x2="19.855" y1="7.101" y2="7.101" gradientUnits="userSpaceOnUse"><stop class="rdy3q2ast"/><stop offset=".006" class="rdy3q2ast"/><stop offset=".253" class="fdp62_bdt"/><stop offset=".298" class="uemnp80iw"/><stop offset=".388" class="o8apaqw0p"/><stop offset=".512" class="rl-9wvb2v"/><stop offset=".596" class="tq27dw91a"/><stop offset=".823" class="axfbzr3yy"/><stop offset=".871" class="bwvp5bbhr"/><stop offset="1" class="fdp62_bdt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cypherock" /></template>
<style>
.axfbzr3yy {
  stop-color: var(--svg-color--e4c878, #e4c878);
}

.bwvp5bbhr {
  stop-color: var(--svg-color--eed688, #eed688);
}

.c7m9ymbpu {
  d: path("m10.442 5.115l3.884 5.679H19.5L14.177 3l-1.343 2.053l.688 1.014l.61-.926l3.178 4.596h-2.313l-4.582-6.71L4.5 11.352h5.262l1.97-2.77l-.68-1.022L9.1 10.296l-2.321-.018z");
}

.fdp62_bdt {
  stop-color: var(--svg-color--fffbcc, #fffbcc);
}

.ft5dv1b6b {
  fill: none;
}

.o8apaqw0p {
  stop-color: var(--svg-color--e7d08f, #e7d08f);
}

.rdy3q2ast {
  stop-color: var(--svg-color--fbc926, #fbc926);
}

.rl-9wvb2v {
  stop-color: var(--svg-color--d1aa55, #d1aa55);
}

.sqdkv5bpv {
  d: path("M12.834 18.947L14.177 21l5.323-7.794h-5.174l-3.884 5.68l-3.663-5.164l2.32-.018l1.952 2.735l.68-1.022l-1.969-2.77H4.5l5.915 8.327l4.582-6.71h2.313l-3.178 4.596l-.61-.927z");
}

.tq27dw91a {
  stop-color: var(--svg-color--c3922e, #c3922e);
}

.uemnp80iw {
  stop-color: var(--svg-color--f8ebb9, #f8ebb9);
}

</style>
