<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="y9cegcu0k"/><path class="w_gxpnbmt"/><path class="dqvyfqwhh"/><path class="zfsk2xbsi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hair-background" /></template>
<style>
.dqvyfqwhh {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.294 13.411v-1.223c.541-.603 1.553-1.642 2.475-1.482c.57.094.8.785.744 1.289c.188-.188.376-.386.597-.537c.165-.117.504-.296.866-.113c.334.165.47.457.532.683l.132-.08c.301-.179.753-.419 1.242-.419h2.824v.941h-2.824c-.348 0-.673.23-.955.41c-.207.131-.433.296-.692.296c-.17 0-.32-.07-.423-.193c-.18-.207-.142-.47-.212-.72c-.297.23-.518.537-.828.753c-.165.113-.504.292-.866.108a.8.8 0 0 1-.297-.24c-.306-.423.113-.823-.061-1.228c-.819.292-1.694 1.134-2.254 1.755");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w_gxpnbmt {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.53 8.705H9.647l.471.47v5.177l-.47.47h1.882l-.47-.47V9.175z");
}

.y9cegcu0k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.zfsk2xbsi {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.353 8.705h-1.882l.47.47v5.177l-.47.47h1.882l-.47-.47V9.175z");
}

</style>
