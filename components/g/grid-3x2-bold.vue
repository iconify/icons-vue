<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="garh2ib3b"/><path class="l397zn2sl"/><path class="tmf0l99tw"/><path class="v51ggtl0s"/><path class="rwrpbcc9w"/><path class="f3wqpy6nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-3x2-bold" /></template>
<style>
.f3wqpy6nq {
  fill: currentColor;
  d: path("M16.083 3.0127C18.511 3.05152 19.8956 3.23937 20.8281 4.17188C21.9997 5.34345 22 7.22876 22 11V11.25H16.083V3.0127Z");
}

.garh2ib3b {
  fill: currentColor;
  d: path("M14.583 20.999C14.3938 20.9992 14.1996 21 14 21H10C9.80044 21 9.60616 20.9992 9.41699 20.999V12.75H14.583V20.999Z");
}

.l397zn2sl {
  fill: currentColor;
  d: path("M7.91699 20.9863C5.489 20.9475 4.10438 20.7606 3.17188 19.8281C2.0003 18.6566 2 16.7712 2 13V12.75H7.91699V20.9863Z");
}

.rwrpbcc9w {
  fill: currentColor;
  d: path("M14.583 11.25H9.41602V3H14.583V11.25Z");
}

.tmf0l99tw {
  fill: currentColor;
  d: path("M22 13C22 16.7712 21.9997 18.6566 20.8281 19.8281C19.8956 20.7606 18.511 20.9475 16.083 20.9863V12.75H22V13Z");
}

.v51ggtl0s {
  fill: currentColor;
  d: path("M7.91602 11.25H2V11C2 7.22876 2.0003 5.34345 3.17188 4.17188C4.10425 3.2395 5.48862 3.05156 7.91602 3.0127V11.25Z");
}

</style>
