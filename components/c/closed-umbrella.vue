<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tl1t0hswm"/><path class="cr2u58xlp"/><path class="oklvezeho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:closed-umbrella" /></template>
<style>
.cr2u58xlp {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M7.367 18.102L9 17.559V16a2 2 0 0 1 1.515-1.94l2.836-.709l.709-2.836A2 2 0 0 1 16 9h1.559l.544-1.632a2.001 2.001 0 0 1 3.686-.263L34 32l-2 2L7.106 21.789a2 2 0 0 1 .261-3.687");
}

.oklvezeho {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("M33 33L13.351 13.351l.709-2.836A2 2 0 0 1 16 9h1.559l.051-.154l15.986 23.558zm-1 1L7.106 21.789a2 2 0 0 1 .261-3.687L9 17.559v-.174l23.409 16.206z");
}

.tl1t0hswm {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M35 35c1-1 0-2 0-2L9 7S7.521 5.479 9 4s3 0 3 0s1 1 2 0s0-2 0-2s-3.521-3.479-7 0C3.5 5.5 7 9 7 9l26 26s1 1 2 0");
}

</style>
