<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGSVf1GdIE" x1="0%" x2="50%" y1="0%" y2="50%"><stop offset="0%" class="oq8n5-bdi"/><stop offset="100%" class="wprzg2kcs"/></linearGradient><linearGradient id="SVG7qlO4bBI" x1=".847%" x2="50.04%" y1="99.193%" y2="50%"><stop offset="0%" class="zcqtrn8_r"/><stop offset="100%" class="ylsedbb7i"/></linearGradient><linearGradient id="SVGrWSFFeTw" x1="92.819%" x2="50%" y1="92.819%" y2="50%"><stop offset="0%" class="abkp5wbjv"/><stop offset="100%" class="iq2-yab2w"/></linearGradient><linearGradient id="SVGh2r5qc8e" x1="82.171%" x2="4.076%" y1="82.171%" y2="4.076%"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="stui2mbih"/></linearGradient><linearGradient id="SVGQq6AR85I" x1="2.904%" x2="50%" y1="97.096%" y2="50%"><stop offset="0%" class="o6cmjepgr"/><stop offset="100%" class="o230slyth"/></linearGradient><linearGradient id="SVGMw1CeblH" x1="0%" x2="100%" y1="50%" y2="50%"><stop offset="0%" class="kcbs64j4b"/><stop offset="100%" class="iruu15saq"/></linearGradient><linearGradient id="SVGKhpqgmGb" x1="50%" x2="-42.783%" y1="50%" y2="-3.568%"><stop offset="0%" class="n-ogeiefg"/><stop offset="100%" class="yuh4cnbgy"/></linearGradient></defs><path fill="url(#SVGSVf1GdIE)" class="kehp56e4h"/><path fill="url(#SVG7qlO4bBI)" class="roafqabsi"/><path fill="url(#SVGrWSFFeTw)" transform="matrix(-1 0 0 -1 256 254.82)" class="z68e6ub7c"/><path fill="url(#SVGh2r5qc8e)" class="gymu6m8wu"/><path fill="url(#SVGQq6AR85I)" class="d6m2dibld"/><path fill="url(#SVGMw1CeblH)" class="dfgknvigj"/><path fill="url(#SVGKhpqgmGb)" transform="matrix(-1 0 0 -1 256 254.82)" class="eiyinbg0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:freedomdefined" /></template>
<style>
.abkp5wbjv {
  stop-color: var(--svg-color--fff18d, #fff18d);
}

.d6m2dibld {
  d: path("M182.605 127.41c0 30.157-24.448 54.604-54.605 54.604s-54.604-24.447-54.604-54.604S97.843 72.806 128 72.806v54.604z");
}

.dfgknvigj {
  d: path("M128 164.541c-20.104 0-36.402-16.298-36.402-36.403S107.896 91.735 128 91.735s36.403 16.298 36.403 36.403H128z");
}

.eiyinbg0u {
  d: path("M146.202 127.41a18.201 18.201 0 1 1-36.403 0a18.201 18.201 0 0 1 36.403 0");
}

.gymu6m8wu {
  d: path("M128 54.605c40.21 0 72.806 32.596 72.806 72.806S168.209 200.216 128 200.216c-40.21 0-72.806-32.596-72.806-72.805H128z");
}

.iq2-yab2w {
  stop-color: var(--svg-color--ffcd01, #ffcd01);
}

.iruu15saq {
  stop-color: var(--svg-color--263cce, #263cce);
  stop-opacity: 0;
}

.kcbs64j4b {
  stop-color: var(--svg-color--263cce, #263cce);
}

.kehp56e4h {
  d: path("M255.41 127.41c0 70.367-57.043 127.41-127.41 127.41S.59 197.777.59 127.41S57.633 0 128 0v127.41z");
}

.n-ogeiefg {
  stop-color: var(--svg-color--652f99, #652f99);
}

.o230slyth {
  stop-color: var(--svg-color--green, green);
}

.o6cmjepgr {
  stop-color: var(--svg-color--00a000, #00a000);
  stop-opacity: 0.259;
}

.oq8n5-bdi {
  stop-color: var(--svg-color--ff5959, #ff5959);
}

.roafqabsi {
  d: path("M128 236.619c-60.314 0-109.209-48.894-109.209-109.209C18.791 67.096 67.686 18.201 128 18.201s109.209 48.895 109.209 109.21H128z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wprzg2kcs {
  stop-color: var(--svg-color--df0000, #df0000);
}

.ylsedbb7i {
  stop-color: var(--svg-color--ffa000, #ffa000);
}

.yuh4cnbgy {
  stop-color: var(--svg-color--502679, #502679);
  stop-opacity: 0.652;
}

.z68e6ub7c {
  d: path("M219.008 127.41c0 50.262-40.746 91.008-91.008 91.008s-91.007-40.746-91.007-91.008S77.74 36.403 128 36.403v91.007z");
}

.zcqtrn8_r {
  stop-color: var(--svg-color--ffb73d, #ffb73d);
}

</style>
