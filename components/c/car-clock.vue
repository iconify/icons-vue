<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gns0hrb9x"/><path class="kp5448bym"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-clock" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.gns0hrb9x {
  d: path("M4.75 11H3.5a1 1 0 0 1-1-1V7.5A1.5 1.5 0 0 1 4 6h1.25L7 3.25a1.5 1.5 0 0 1 1.25-.75h4.5a1.5 1.5 0 0 1 1.25.75L15.75 6H18a1.5 1.5 0 0 1 1.5 1.5V10a1 1 0 0 1-1 1h-2m-8.25 0H13");
}

.kp5448bym {
  d: path("M4.75 11a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm11.141 1.327q.143-.123.257-.274t.192-.323q.079-.172.12-.356q.04-.185.04-.374q0-.086-.008-.172t-.026-.169q-.016-.085-.041-.167t-.058-.162q-.033-.079-.074-.155t-.088-.147t-.102-.138t-.116-.127t-.127-.116q-.066-.054-.138-.102q-.071-.048-.147-.088q-.076-.041-.155-.074q-.08-.033-.162-.058t-.167-.041t-.169-.026t-.172-.008q-.086 0-.172.008t-.169.026q-.085.016-.167.041t-.162.058q-.079.033-.155.074t-.147.088q-.072.048-.138.102q-.067.055-.127.116q-.061.06-.116.127q-.054.066-.102.138q-.048.071-.088.147q-.041.076-.074.155q-.033.08-.058.162t-.041.167t-.026.169T13 11q0 .086.008.172t.026.169q.016.085.041.167t.058.162q.033.079.074.155t.088.147q.048.072.102.138q.055.067.116.127q.06.061.127.116q.066.054.138.102q.071.048.147.088q.076.041.155.074q.08.033.162.058t.167.041t.169.026t.172.008q.169 0 .335-.032M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
