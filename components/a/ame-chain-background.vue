<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xd37n8bzj"/><path fill="url(#SVG7EScP4mf)" clip-rule="evenodd" class="zcu5zfb-s"/><path fill="url(#SVGad4kEdvV)" clip-rule="evenodd" class="wemcupo_i"/><path fill="url(#SVGMLFnceRo)" clip-rule="evenodd" class="pas5n5bnx"/><path fill="url(#SVGF7eYRb1E)" clip-rule="evenodd" class="hoa076bgh"/><path fill="url(#SVGHvSigb0M)" clip-rule="evenodd" class="x78pf5k0a"/></g><defs><linearGradient id="SVG7EScP4mf" x1="6.05" x2="18.061" y1="6.896" y2="16.164" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient><linearGradient id="SVGad4kEdvV" x1="12.305" x2="15.685" y1="10.818" y2="11.691" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient><linearGradient id="SVGMLFnceRo" x1="10.721" x2="13.671" y1="9.867" y2="13.573" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient><linearGradient id="SVGF7eYRb1E" x1="10.491" x2="13.91" y1="10.807" y2="11.7" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient><linearGradient id="SVGHvSigb0M" x1="11.447" x2="13.341" y1="11.158" y2="11.574" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ame-chain-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hoa076bgh {
  fill-rule: evenodd;
  d: path("m10.778 13.456l-.5-.272v-2.132l1.657.887c0 .525-.01 1.62-.011 2.14l-.487-.263l.016-1.464l-.031-.016l-.054-.03l-.014-.006l-.01 1.463l-.475-.258l.015-1.463l-.098-.053z");
}

.pas5n5bnx {
  fill-rule: evenodd;
  d: path("m12 9.973l-1.725.928l.702.383L12 10.739l1.026.544l.702-.382z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wemcupo_i {
  fill-rule: evenodd;
  d: path("M13.73 12.546v.656l-1.62.883l-.016-2.146c.579-.32 1.06-.569 1.636-.876v.614l-1.151.606v.129l1.15-.612v.622l-1.15.606v.128z");
}

.wr1fd059m {
  stop-color: var(--svg-color--d40000, #d40000);
}

.x78pf5k0a {
  fill-rule: evenodd;
  d: path("m11.34 11.275l.656-.357l.67.362l-.665.367z");
}

.xd37n8bzj {
  fill: var(--svg-color--640000, #640000);
  d: path("M24 0H0v24h24z");
}

.yq0k8w5lc {
  stop-color: var(--svg-color--f70, #f70);
}

.zcu5zfb-s {
  fill-rule: evenodd;
  d: path("m18.996 12.038l-6.7 3.877v2.064l6.7-3.879v2.06l-6.315 3.657a1.37 1.37 0 0 1-1.365 0L8.56 18.222v-7.76L6.777 9.431v7.76L5 16.16V8.843a1.37 1.37 0 0 1 .682-1.186l2.756-1.595l6.697 3.88l1.783-1.033l-6.698-3.877L12.003 4l6.314 3.658A1.37 1.37 0 0 1 19 8.844zM9.62 7.442L7.074 8.916L8.857 9.95l2.547-1.474zm5.812 5.971l1.783-1.034V9.43l-1.783 1.033zM9.156 16.51l2.547 1.475v-2.069L9.156 14.44zm5.685-2.754v-3.29L12 8.817l-2.843 1.646v3.291L12 15.401z");
}

</style>
