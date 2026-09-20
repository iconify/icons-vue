<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dcr03ubbg"/><path class="gsb-z7bta"/><path class="fj-88bt7c"/><path class="gv0-nsboz"/><path class="dtzamj1ga"/><path class="enkxsx84t"/><path class="rtcbky81c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ankreth" /></template>
<style>
.dcr03ubbg {
  fill: var(--svg-color--ffe81c, #FFE81C);
  d: path("M3.111 7.928v7.656c0 .61.3 1.178.789 1.483l7.567 4.711c.5.306 1.105.295 1.594-.027l7.073-4.678a1.75 1.75 0 0 0 .755-1.462V8.418c0-.6-.289-1.156-.755-1.461L13.022 2.25a1.46 1.46 0 0 0-1.533-.06L3.961 6.405a1.73 1.73 0 0 0-.85 1.522");
}

.dtzamj1ga {
  fill: var(--svg-color--332e06, #332E06);
  d: path("M12.001 10.334V6.445L14.779 12z");
}

.enkxsx84t {
  fill: var(--svg-color--141302, #141302);
  d: path("M12.001 13.667v-3.333L14.779 12z");
}

.fj-88bt7c {
  fill: var(--svg-color--332e06, #332E06);
  d: path("m12.001 14.223l2.778-1.667L12 17z");
}

.ft5dv1b6b {
  fill: none;
}

.gsb-z7bta {
  fill: var(--svg-color--8c800f, #8C800F);
  d: path("m12 14.223l-2.777-1.667L12 17z");
}

.gv0-nsboz {
  fill: var(--svg-color--8c800f, #8C800F);
  d: path("M12 10.334V6.445L9.223 12z");
}

.rtcbky81c {
  fill: var(--svg-color--383306, #383306);
  d: path("M12 13.667v-3.333L9.223 12z");
}

</style>
