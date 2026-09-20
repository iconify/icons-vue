<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG24r4DeZt)" clip-rule="evenodd" class="l7yr59qmr"/><path fill="url(#SVGsj68ub3S)" clip-rule="evenodd" class="uwn4tvbik"/><path fill="url(#SVG8qfAsbYN)" clip-rule="evenodd" class="rue91q8jm"/><path fill="url(#SVGE4bLzbmq)" clip-rule="evenodd" class="mhffkccij"/><path fill="url(#SVG3fdyke0p)" clip-rule="evenodd" class="n6b4tmbco"/><defs><linearGradient id="SVG24r4DeZt" x1="5.2" x2="18.765" y1="6.258" y2="16.891" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient><linearGradient id="SVGsj68ub3S" x1="12.349" x2="16.204" y1="10.67" y2="11.682" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient><linearGradient id="SVG8qfAsbYN" x1="10.538" x2="13.844" y1="9.6" y2="13.821" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient><linearGradient id="SVGE4bLzbmq" x1="10.276" x2="14.175" y1="10.657" y2="11.692" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient><linearGradient id="SVG3fdyke0p" x1="11.368" x2="13.53" y1="11.053" y2="11.535" gradientUnits="userSpaceOnUse"><stop class="wr1fd059m"/><stop offset="1" class="yq0k8w5lc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ame-chain" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l7yr59qmr {
  fill-rule: evenodd;
  d: path("m19.995 12.043l-7.656 4.362v2.322l7.656-4.364v2.316l-7.216 4.115a1.58 1.58 0 0 1-1.561 0L8.068 19v-8.73L6.03 9.11v8.73L4 16.68V8.45c0-.27.072-.537.209-.77a1.55 1.55 0 0 1 .571-.565L7.93 5.32l7.653 4.365l2.037-1.162L9.965 4.16L12.003 3l7.217 4.115c.237.135.434.33.571.564s.21.5.209.77zM9.281 6.872L6.37 8.53l2.037 1.163l2.91-1.658zm6.642 6.718l2.038-1.163v-3.32l-2.038 1.162zM8.75 17.072l2.912 1.66v-2.327l-2.912-1.66zm6.498-3.097v-3.703L12 8.42l-3.25 1.852v3.703L12 15.827z");
}

.mhffkccij {
  fill-rule: evenodd;
  d: path("m10.604 13.638l-.573-.306v-2.399l1.894.999c0 .59-.01 1.822-.012 2.406l-.556-.296l.017-1.646l-.035-.018l-.06-.033l-.017-.008l-.013 1.646l-.542-.29l.018-1.646l-.112-.06z");
}

.n6b4tmbco {
  fill-rule: evenodd;
  d: path("m11.245 11.185l.75-.402l.767.407l-.76.413z");
}

.rue91q8jm {
  fill-rule: evenodd;
  d: path("m12 9.72l-1.971 1.044l.802.43L12 10.58l1.173.612l.802-.43z");
}

.uwn4tvbik {
  fill-rule: evenodd;
  d: path("M13.978 12.614v.738l-1.852.994l-.018-2.414c.661-.36 1.21-.64 1.87-.986v.691l-1.316.681v.145l1.315-.688v.7l-1.315.681v.145z");
}

.wr1fd059m {
  stop-color: var(--svg-color--d40000, #d40000);
}

.yq0k8w5lc {
  stop-color: var(--svg-color--f70, #f70);
}

</style>
