<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkv-wjbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-sleep-sound" /></template>
<style>
.wkv-wjbsw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.665 2.018q.18.041.321.16q.113.097.181.23q.068.132.081.281t-.034.291t-.142.256q-2.724 3.206-.778 6.937q1.044 2 2.732 2.813q-.034.059-.065.12l-.032.066q-.179.395-.179.828v1.754q-3.5.123-3.5 3.746q0 .42.047.792q-1.823.136-3.683-.506q-3.482-1.2-5.186-4.466t-.697-6.808q1.008-3.543 4.174-5.424q3.167-1.88 6.76-1.07M17 14v3.127Q16.564 17 16 17q-2.5 0-2.5 2.5T16 22t2.5-2.5v-4.286l1.915.957q.133.067.282.077q.149.011.29-.036q.142-.048.254-.145q.113-.098.18-.232q.067-.133.077-.282q.011-.149-.036-.29q-.048-.142-.145-.254q-.098-.113-.232-.18l-3-1.5q-.158-.079-.335-.079q-.093 0-.184.023t-.173.067t-.151.108t-.12.142q-.023.036-.043.075Q17 13.823 17 14m0 5.5q0 1-1 1t-1-1t1-1t1 1");
}

</style>
