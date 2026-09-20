<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGHJYWIbSS)" class="uwwb_ccdh"/><path fill="url(#SVGwr1kycXi)" class="a-2ewd__i"/><path fill="url(#SVGRGl0AcZa)" class="ap7t2-w5z"/><defs><linearGradient id="SVGHJYWIbSS" x1="14.375" x2="4.315" y1="3.949" y2="18.562" gradientUnits="userSpaceOnUse"><stop class="qj2numbbd"/><stop offset="1" class="fiy11wxak"/></linearGradient><linearGradient id="SVGwr1kycXi" x1="7.123" x2="13.66" y1="3.289" y2="21.584" gradientUnits="userSpaceOnUse"><stop offset=".05" class="skzipr1zn"/><stop offset=".93" class="te1o4ry8t"/></linearGradient><linearGradient id="SVGRGl0AcZa" x1="2.998" x2="17.713" y1="17.556" y2="17.556" gradientUnits="userSpaceOnUse"><stop offset=".16" class="qj2numbbd"/><stop offset="1" class="fiy11wxak"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ata" /></template>
<style>
.a-2ewd__i {
  d: path("M16.51 5.23c.342.36.68.77.944 1.237l2.755 4.88c1.906 3.386.169 7.547-3.093 8.924l-.781.22c2.334-2.492 1.788-5.207 1.136-6.343a2 2 0 0 0-.09-.186l-3.784-6.516a1.57 1.57 0 0 0-2.12-.574A5.01 5.01 0 0 1 16.51 5.23");
}

.ap7t2-w5z {
  d: path("M16.363 20.474c2.334-2.491 1.822-5.072 1.176-6.213c.421 1-.377 1.956-1.507 1.956H8.059c-3.39-.416-4.296-2.845-4.577-4.009l-.023-.123c-1.636 3.992 1.288 8.63 5.786 8.63h5.33c.715 0 1.266-.129 1.783-.241z");
}

.fiy11wxak {
  stop-color: var(--svg-color--ab1414, #ab1414);
}

.ft5dv1b6b {
  fill: none;
}

.qj2numbbd {
  stop-color: var(--svg-color--fcca02, #fcca02);
}

.skzipr1zn {
  stop-color: var(--svg-color--aa1215, #aa1215);
}

.te1o4ry8t {
  stop-color: var(--svg-color--fdcb02, #fdcb02);
}

.uwwb_ccdh {
  d: path("M16.51 5.231a6.225 6.225 0 0 0-9.952 1.237l-2.75 4.88c-.14.242-.259.495-.36.743l.011.022c.276 1.164 1.069 3.88 4.46 4.29c.185.023.354.034.517.034a1.56 1.56 0 0 1-1.548-1.553c0-.271.07-.539.204-.775l3.8-6.623c.13-.225.417-.506.608-.636c.939-1.012 2.553-2.018 5.01-1.619");
}

</style>
