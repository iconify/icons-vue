<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="flru3ydsf"/><path class="n8h_asbpa"/><path class="en0ilclhm"/><path class="tuemldd6j"/><path class="jjyhk_byw"/><path class="bgx4hfbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-south-sudan" /></template>
<style>
.bgx4hfbjl {
  fill: var(--svg-color--fcdd09, #fcdd09);
  d: path("m8.249 17.917l1.777-2.446l-2.875.934l-1.776-2.445v3.023l-2.875.934l2.875.934v3.022l1.776-2.445l2.875.934z");
}

.en0ilclhm {
  fill: var(--svg-color--da121a, #da121a);
  d: path("M0 12h36v12H0z");
}

.flru3ydsf {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5H4a4 4 0 0 0-4 4v3h36V9a4 4 0 0 0-4-4");
}

.jjyhk_byw {
  fill: var(--svg-color--0f47af, #0f47af);
  d: path("M1.351 6.004C.522 6.737 0 7.808 0 9.267v18c0 .926.522 1.997 1.351 2.729L17.5 18z");
}

.n8h_asbpa {
  fill: var(--svg-color--078930, #078930);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-3H0z");
}

.tuemldd6j {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 12h36v2H0zm0 10h36v2H0z");
}

</style>
