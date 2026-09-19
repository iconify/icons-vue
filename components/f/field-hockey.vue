<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path id="SVGz68sCcHF" class="v0ttxabqc"/><path class="vval7mbtb"/><path class="zaf674rrz"/><use href="#SVGz68sCcHF"/><path class="qa9p3-9mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:field-hockey" /></template>
<style>
.qa9p3-9mo {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M31.1 27.3s-1.9 2.3-3.4 4.1c2.5 6.6-4 17.8-4 17.8s10.6-14 7.4-21.9");
}

.v0ttxabqc {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("M49.5 37.1c-6.9 0-12.5 5.6-12.5 12.5s5.6 12.5 12.5 12.5S62 56.4 62 49.5c0-6.8-5.6-12.4-12.5-12.4");
}

.vval7mbtb {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M53.5 2L18.6 41.8c-1.5 1.8-4.3 2-6.2.4s-2.2-4.3-.6-6.2c1.5-1.8 1.2-4.6-.6-6.2c-1.9-1.6-4.6-1.4-6.2.4C.4 35.7 1.3 44 6.9 48.7c5.5 4.7 13.6 4.2 18.3-1L62 2z");
}

.zaf674rrz {
  fill: var(--svg-color--c7e755, #c7e755);
  d: path("M38.3 31.4s.5-6.2 1.2-8.1C41.8 16.8 55.6 2 55.6 2h-2.9L31.1 27.3c-.2 11.9-7.5 21.9-7.5 21.9c2.3-1.1 14.7-17.8 14.7-17.8");
}

</style>
