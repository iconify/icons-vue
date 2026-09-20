<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="h3wwcsbfn"/><ellipse transform="rotate(-60 27.574 28.49)" class="mtmmm4scg"/><path class="p8hv3lbkz"/><path class="o_7si_bnq"/><path class="hol3s8beh"/><ellipse transform="rotate(-30 8.424 28.489)" class="i1txikrow"/><path class="d2lg80b2u"/><path class="gnnzacblw"/><path class="yyxb25y7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:folded-hands" /></template>
<style>
.d2lg80b2u {
  fill: var(--svg-color--f9ca55, #f9ca55);
  d: path("M16.061.011a2.115 2.115 0 0 0-2.333 2.103c0 .78-.184 10.319-.184 10.319L17.895 18l.062-15.765c0-1.106-.795-2.114-1.896-2.224");
}

.gnnzacblw {
  fill: var(--svg-color--ffdc5d, #ffdc5d);
  d: path("M17.125 4.323c0-1.099-.852-1.989-1.903-1.989s-1.903.891-1.903 1.989c0 0-.535 5.942-1.192 9.37c-.878 1.866-1.369 4.682-1.261 6.248c-.054.398-5.625 5.006-5.625 5.006C5.522 26.76 7.5 31.102 10 33.106l3.521-2.924c2.885-.404 4.458-3.331 4.458-4.264c0-2.984-.854-21.595-.854-21.595");
}

.h3wwcsbfn {
  fill: var(--svg-color--50a5e6, #50a5e6);
  d: path("M30 22c-3 0-6.688 7.094-7 10c-.421 3.915 2 4 2 4h11V26s-3.438-4-6-4");
}

.hol3s8beh {
  fill: var(--svg-color--50a5e6, #50a5e6);
  d: path("M6 22c3 0 6.688 7.094 7 10c.421 3.915-2 4-2 4H0V26s3.438-4 6-4");
}

.i1txikrow {
  cx: 8.426px;
  cy: 28.489px;
  fill: var(--svg-color--1c6399, #1c6399);
  rx: 1.638px;
  ry: 5.848px;
}

.mtmmm4scg {
  cx: 27.574px;
  cy: 28.489px;
  fill: var(--svg-color--1c6399, #1c6399);
  rx: 5.848px;
  ry: 1.638px;
}

.o_7si_bnq {
  fill: var(--svg-color--ffdc5d, #ffdc5d);
  d: path("M18.875 4.323c0-1.099.852-1.989 1.903-1.989s1.903.891 1.903 1.989c0 0 .535 5.942 1.192 9.37c.878 1.866 1.369 4.682 1.261 6.248c.054.398 5.625 5.006 5.625 5.006c-.281 1.813-2.259 6.155-4.759 8.159l-3.521-2.924c-2.885-.404-4.458-3.331-4.458-4.264c0-2.984.854-21.595.854-21.595");
}

.p8hv3lbkz {
  fill: var(--svg-color--f9ca55, #f9ca55);
  d: path("M20.086 0c1.181 0 2.138.957 2.138 2.138c0 .789.668 10.824.668 10.824L17.948 18V2.138C17.948.957 18.905 0 20.086 0");
}

.yyxb25y7a {
  fill: var(--svg-color--f9ca55, #f9ca55);
  d: path("M17.958 25.823a.75.75 0 0 1-.75-.75V2.792a.75.75 0 0 1 1.5 0v22.282a.75.75 0 0 1-.75.749");
}

</style>
