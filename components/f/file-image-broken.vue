<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b4cd0mb_l"/><path class="e0cmz0boh"/><path class="t4qaumccy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-image-broken" /></template>
<style>
.b4cd0mb_l {
  d: path("M2 12.5852L3.8225 10.9905C4.77066 10.1609 6.19968 10.2085 7.09055 11.0994L11.5539 15.5628C12.269 16.2778 13.3946 16.3753 14.2219 15.7939L14.5322 15.5758C15.7228 14.7391 17.3335 14.836 18.4152 15.8095L21.7692 18.8281");
}

.e0cmz0boh {
  d: path("M13 2.2627V5.0003C13 7.35732 13 8.53583 13.7322 9.26806C14.4645 10.0003 15.643 10.0003 18 10.0003H21.58");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t4qaumccy {
  stroke-linejoin: round;
  d: path("M2 10V14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C21.4816 20.1752 21.7706 19.3001 21.8985 18M22 14V13.5629C22 11.8083 22 10.931 21.654 10.1541C21.308 9.3772 20.6559 8.79032 19.3517 7.61654L15.3929 4.05365C14.2651 3.03857 13.7012 2.53104 13.0092 2.26552C12.3173 2 11.5548 2 10.0298 2C6.23869 2 4.34315 2 3.17157 3.17157C2.51839 3.82475 2.22937 4.69989 2.10149 6");
}

</style>
