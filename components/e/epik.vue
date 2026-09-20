<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="tr7xbqb4y"/><path fill="url(#SVGmqZOleIW)" class="wj_q9hbwi"/><path class="xx5_o3b8y"/><defs><linearGradient id="SVGmqZOleIW" x1="24.167" x2="23.76" y1="6.416" y2="18.358" gradientUnits="userSpaceOnUse"><stop class="lgq976b8j"/><stop offset=".17" class="fmfw85b0z"/><stop offset=".24" class="fmfw85b0z"/><stop offset=".32" class="lgq976b8j"/><stop offset=".42" class="fmfw85b0z"/><stop offset=".58" class="fmfw85b0z"/><stop offset=".67" class="lgq976b8j"/><stop offset=".76" class="fmfw85b0z"/><stop offset=".84" class="fmfw85b0z"/><stop offset="1" class="lgq976b8j"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:epik" /></template>
<style>
.fmfw85b0z {
  stop-color: var(--svg-color--fefcff, #fefcff);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.lgq976b8j {
  stop-color: var(--svg-color--fefcff, #fefcff);
}

.tr7xbqb4y {
  fill: var(--svg-color--683ca4, #683ca4);
  fill-rule: evenodd;
  d: path("M12 21a8.997 8.997 0 0 0 9-9a9 9 0 0 0-9-9a9 9 0 0 0 0 18m0-1a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.wj_q9hbwi {
  d: path("M11.499 6.74c0-.41.33-.74.735-.74H13v11.016c0 .545-.44.985-.985.985H11.5z");
}

.xx5_o3b8y {
  fill: var(--svg-color--fefcff, #fefcff);
  d: path("M14.5 11.22h-.17c-2.38 0-4.595 0-4.595-1.55c0-1.72 3.65-1.414 5.13-.7c.28.136.675.11.87-.134l.4-.5a.23.23 0 0 0 .01-.283a.2.2 0 0 0-.075-.067A8.55 8.55 0 0 0 12.15 7C9.73 7 7.68 8.126 7.68 9.676c0 1.185 1.25 1.84 1.96 2.05h-.01c-.725.185-2.36 1.08-2.36 2.39c0 1.64 2.175 2.885 4.735 2.885c1.82 0 3.584-.69 4.34-1.11a.25.25 0 0 0 .07-.375L16 14.99c-.21-.26-.63-.285-.93-.14c-1.56.75-5.49 1.095-5.49-.735c0-1.62 2.165-1.615 4.635-1.615h.285z");
}

</style>
