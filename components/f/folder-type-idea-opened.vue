<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGEDDnMbnv" x1=".85" x2="62.62" y1="62.72" y2="1.81" gradientUnits="userSpaceOnUse"><stop offset="0" class="ec6hdqb4b"/><stop offset=".43" class="cm-b0x9yw"/><stop offset=".99" class="fxr1xyban"/></linearGradient></defs><path class="gm0s3ubbl"/><path class="b1m4d4byg"/><path fill="url(#SVGEDDnMbnv)" transform="translate(10 10)scale(.3125)" class="imyc9yulz"/><path class="tb2ha8k8k"/><path class="cxv6nvb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-idea-opened" /></template>
<style>
.b1m4d4byg {
  fill: var(--svg-color--dbd47b, #dbd47b);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.cm-b0x9yw {
  stop-color: var(--svg-color--ff021d, #ff021d);
}

.cxv6nvb8s {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.375 24.688h-5.312v1.25h5.312z");
}

.ec6hdqb4b {
  stop-color: var(--svg-color--ff9419, #ff9419);
}

.fxr1xyban {
  stop-color: var(--svg-color--e600ff, #e600ff);
}

.gm0s3ubbl {
  fill: var(--svg-color--dbd47b, #dbd47b);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.imyc9yulz {
  d: path("M20.34 3.66L3.66 20.34A12.5 12.5 0 0 0 0 29.18V59c0 2.76 2.24 5 5 5h29.82c3.32 0 6.49-1.32 8.84-3.66l16.68-16.68c2.34-2.34 3.66-5.52 3.66-8.84V5c0-2.76-2.24-5-5-5H29.18c-3.32 0-6.49 1.32-8.84 3.66");
}

.tb2ha8k8k {
  d: path("M25 15H12.5v12.5H25z");
}

</style>
