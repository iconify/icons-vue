<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGg46XmbAL)" class="gtn2b8b1p"/><path fill="url(#SVGv4Sj8bIj)" class="mk5clrb9c"/><defs><linearGradient id="SVGg46XmbAL" x1="28.767" x2="14.923" y1="14.777" y2="-.271" gradientUnits="userSpaceOnUse"><stop class="vtoc0-r2p"/><stop offset="1" class="v28ua0nqc"/></linearGradient><linearGradient id="SVGv4Sj8bIj" x1="10.466" x2="9.607" y1="10.325" y2="9.385" gradientUnits="userSpaceOnUse"><stop class="vtoc0-r2p"/><stop offset="1" class="v28ua0nqc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:karura" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gtn2b8b1p {
  d: path("m15.919 3l-5.541 5.035a3.13 3.13 0 0 1-2.096.814l-1.651.004l-.006-5.852H3.64v16.725h1.629c.91 0 1.76-.483 2.205-1.276l.01-.015c.295-.53.443-1.58.415-2.297c-.065-1.638-.328-2.064-.328-2.064c-.056 1.123-1.228 1.184-1.228 1.184c.834-.796.38-1.4.38-1.4c-1.478 1.052-1.846-.07-1.875-.172c.047.04.467.39 1.265-.704c.845-1.157 1.97-3.085 2.687-3.58c.718-.498 1.399-.457 1.399-.457s.392-.53 1.429-.972c1.036-.44 1.701.205 1.701.205c-1.06.855-2.5 2.259-2.58 4.272c-.064 1.628 3.446 4.422 2.83 8.55c.369-.937.517-1.876.39-3.038c-.101-.938-.706-2.897-.706-2.897l3.371 4.659h3.728l-7.286-10.01L20.361 3z");
}

.mk5clrb9c {
  d: path("M9.13 10.202c-.235.39-.235.51-.235.51s.822-.14 1.046-1.118c0 0-.525.135-.811.608");
}

.v28ua0nqc {
  stop-color: var(--svg-color--ff4c3b, #ff4c3b);
}

.vtoc0-r2p {
  stop-color: var(--svg-color--e40c5b, #e40c5b);
}

</style>
