<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kblr0i4fy"/><path class="l9fa_acaf"/><path class="neilwg2ov"/><path class="wdxo4iqka"/><path class="tkulpsbjv"/><path class="s3f6isbfy"/><path class="sok0n3swb"/><path class="v39z71izp"/><path class="mqp9-h64y"/><path class="v1wdoipqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:confetti-minimalistic-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kblr0i4fy {
  d: path("M13.3057 18.2975L8.23724 19.987L8.23723 19.987C5.47182 20.9088 4.08912 21.3697 3.35924 20.6398C2.62936 19.9099 3.09026 18.5272 4.01207 15.7618L5.70156 10.6933C6.46758 8.39525 6.85059 7.24623 7.75684 7.03229C8.6631 6.81835 9.51953 7.67478 11.2324 9.38764L14.6114 12.7666C16.3242 14.4795 17.1807 15.3359 16.9667 16.2422");
}

.l9fa_acaf {
  d: path("M12.2351 18.3462C12.2351 18.3462 11.477 16.0651 11.477 14.5553C11.477 13.0456 12.2351 10.7644 12.2351 10.7644M8.06517 19.4834C8.06517 19.4834 7.42484 16.7316 7.307 14.9344C7.11229 11.9652 8.06517 7.35266 8.06517 7.35266");
}

.mqp9-h64y {
  stroke-linejoin: round;
  d: path("M19.4375 15.6926H19.4376");
}

.neilwg2ov {
  d: path("M14.5093 10.0061L14.6533 9.28614C14.7986 8.55924 15.3224 7.96597 16.0256 7.73155C16.7289 7.49714 17.2526 6.90387 17.398 6.17697L17.542 5.45703");
}

.s3f6isbfy {
  stroke-linejoin: round;
  d: path("M7.30664 4.32007H7.30674");
}

.sok0n3swb {
  stroke-linejoin: round;
  d: path("M17.8789 10.1208H17.879");
}

.tkulpsbjv {
  d: path("M10.5352 3C10.1977 3.55206 10.2823 4.26344 10.7399 4.72097L10.8377 4.81885C11.2309 5.21201 11.3759 5.78959 11.215 6.32182");
}

.v1wdoipqz {
  stroke-linejoin: round;
  d: path("M20.2266 8.22644H20.2267");
}

.v39z71izp {
  stroke-linejoin: round;
  d: path("M14.1299 4.96533H14.13");
}

.wdxo4iqka {
  d: path("M17.5688 12.2536L17.7817 12.3765C18.4388 12.7558 19.265 12.6722 19.8327 12.1688C20.3468 11.7129 21.0789 11.5973 21.7085 11.8725L22 12");
}

</style>
