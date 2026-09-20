<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGWjMSacFj" x1="-675.043" x2="-660.949" y1="-738.859" y2="-752.956" gradientTransform="matrix(1 0 0 -1 688.886 -724.637)" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGquZWRb7f" x1="-660.289" x2="-674.388" y1="-752.297" y2="-738.195" href="#SVGWjMSacFj"/></defs><path class="kqg603bna"/><path fill="url(#SVGWjMSacFj)" class="hpqcrjqbc"/><path fill="url(#SVGquZWRb7f)" class="de2vnubmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-json-official-opened" /></template>
<style>
.de2vnubmk {
  d: path("M20.978 16.171c-2.92-1.008-6.5 1.4-6.5 6.229c0 7.882 5.832 8.6 6.539 8.6a9.994 9.994 0 0 0 0-19.988c1.216-.168 6.558 1.319 6.558 8.63C27.579 24.405 23.59 27 21 25.9a5.08 5.08 0 0 1-2.936-4.869a5.12 5.12 0 0 1 2.914-4.86");
}

.hpqcrjqbc {
  d: path("M20.983 25.883c4.418 6.032 8.742-1.683 8.735-6.323c-.007-5.485-5.559-8.552-8.739-8.552a9.994 9.994 0 0 0 0 19.988c-.993-.143-4.307-.857-4.35-8.5c-.03-5.168 1.683-7.232 4.344-6.325a5.08 5.08 0 0 1 2.935 4.869a5.09 5.09 0 0 1-2.925 4.843");
}

.kqg603bna {
  fill: var(--svg-color--9b9b9b, #9b9b9b);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
