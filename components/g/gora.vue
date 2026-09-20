<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGraJvEbNj)" clip-rule="evenodd" class="h7zaeqb1j"/><defs><linearGradient id="SVGraJvEbNj" x1="4.659" x2="18.57" y1="10.364" y2="16.34" gradientUnits="userSpaceOnUse"><stop class="syhgycynn"/><stop offset=".35" class="kp1i5sb1z"/><stop offset=".48" class="q5kcf5nvs"/><stop offset=".79" class="ppcaokpxh"/><stop offset="1" class="bh0wvzbmf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gora" /></template>
<style>
.bh0wvzbmf {
  stop-color: var(--svg-color--dcfdf0, #dcfdf0);
}

.ft5dv1b6b {
  fill: none;
}

.h7zaeqb1j {
  fill-rule: evenodd;
  d: path("M8.65 4.589c-.392 0-.699.132-.916.45L3.679 10.94c-.254.37-.27.847-.053 1.233l1.482 2.547a4.2 4.2 0 0 1 .52-1.435l3.138-5.738a1.66 1.66 0 0 1 1.45-.842h4.135a.98.98 0 0 1 .715.318l1.603-1.821c-.338-.54-.963-.614-1.196-.614H8.645zM5.58 15.536l1.937 3.345c.212.36.603.524 1.027.524h7.32c.44 0 .848-.18 1.049-.56l3.478-6.803c.418-.778-.16-1.636-1.048-1.636h-1.641c.063.106.106.149.127.265c.05.394-.01.793-.175 1.154l-.01.01l-2.435 4.103c-.302.455-.821.82-1.377.82H10.19c-.582 0-1.122-.396-1.424-.889l-1.725-2.81v-.006c-.101-.175-.212-.497-.233-.905l-.773 1.376c-.111.18-.265.503-.376.884c-.106.37-.159.773-.08 1.133zm1.884-4.558L9.18 7.776c.212-.37.604-.54 1.038-.54h4.134c.37 0 .524.323.662.603l2.223-2.583l-.069-.132c-.429-.847-1.255-1.064-1.63-1.064h-6.83c-.545 0-1.059.264-1.371.72l-4.05 5.896a1.61 1.61 0 0 0-.068 1.732l3.89 6.706c.292.514.842.826 1.435.826h7.32c.615 0 1.181-.339 1.467-.873l3.483-6.803a1.635 1.635 0 0 0-1.471-2.392H13.52c-.593 0-1.138.312-1.435.82l-1.408 2.313c-.27.466.069 1.112.614 1.112h4.426l-.9 1.567a1.21 1.21 0 0 1-.995.55H10.18a1.22 1.22 0 0 1-1.017-.598l-1.715-2.821a2.35 2.35 0 0 1 .01-1.837zm8.56 2.61H11.29a.233.233 0 0 1-.2-.35l1.397-2.313c.211-.365.603-.513 1.032-.513h3.197c.768 0 .741.656.498 1.217z");
}

.kp1i5sb1z {
  stop-color: var(--svg-color--eefdfe, #eefdfe);
}

.ppcaokpxh {
  stop-color: var(--svg-color--e9f6fa, #e9f6fa);
}

.q5kcf5nvs {
  stop-color: var(--svg-color--77d264, #77d264);
}

.syhgycynn {
  stop-color: var(--svg-color--5ccb38, #5ccb38);
}

</style>
