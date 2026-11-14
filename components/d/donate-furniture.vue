<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ubfxvcc-f"/><path class="topdgy0ld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donate-furniture" /></template>
<style>
.topdgy0ld {
  d: path("M5.25 9.25V6a2.5 2.5 0 0 1 2.5-2.5h8.5a2.5 2.5 0 0 1 2.5 2.5v3.25M5.5 18v2.5m12.5-6V21m-2.75-2.75L18 21l2.75-2.75");
}

.ubfxvcc-f {
  d: path("M11.599 18H3.5v-7q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026t.172-.008q.086 0 .172.008t.169.026q.085.016.167.041t.162.058q.079.033.155.074t.147.088q.072.048.138.102q.067.055.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167t.026.169Q7 10.914 7 11v2.5h8.15M17 11.75V11q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026t.172-.008q.086 0 .172.008t.169.026q.085.016.167.041t.162.058t.155.074t.147.088q.072.048.138.102q.067.055.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167t.026.169q.008.086.008.172v.701");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
