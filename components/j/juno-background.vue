<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="of3nnh91f"/><path class="i_unt2b3d"/><path class="emgh5ibkv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:juno-background" /></template>
<style>
.emgh5ibkv {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.47 7.294c0-.235-.15-.47-.471-.47s-.47.235-.47.47v2.142l-1.59-1.592c-.128-.122-.363-.14-.589.08c-.226.226-.207.462-.08.589l1.605 1.604H8.592c-.179 0-.358.212-.358.47c0 .26.18.472.358.472h2.268l-1.604 1.604c-.123.127-.104.4.08.588c.183.184.46.203.588.08l1.605-1.604v3.096h-.941c-.306 0-.47.212-.47.47c0 .26.173.471.47.471h.94v.942c0 .235.212.47.471.47s.47-.235.47-.47v-.942h.942a.465.465 0 0 0 .471-.47a.466.466 0 0 0-.47-.47h-.942v-3.112l1.62 1.62c.126.122.404.103.587-.08c.184-.189.203-.462.076-.589l-1.604-1.604h2.257c.179 0 .358-.151.358-.471s-.18-.47-.358-.47h-2.268l1.605-1.605c.122-.127.146-.363-.08-.589c-.226-.22-.461-.202-.588-.08L12.47 9.45z");
}

.ft5dv1b6b {
  fill: none;
}

.i_unt2b3d {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 19.53c4.235 0 7.53-3.53 7.53-7.53S16.234 4.47 12 4.47S4.47 8 4.47 12s3.295 7.53 7.53 7.53M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0");
}

.of3nnh91f {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
