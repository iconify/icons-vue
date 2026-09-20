<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x2wn8kbnc"/><path class="g6m2-1bfe"/><path class="ww1wtk_kp"/><path class="avs9oiybu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:delicious" /></template>
<style>
.avs9oiybu {
  fill: var(--svg-color--39f, #39F);
  d: path("M128 0h128v128H128z");
}

.g6m2-1bfe {
  fill: var(--svg-color--333, #333);
  d: path("M0 128h128v128H0z");
}

.ww1wtk_kp {
  fill: var(--svg-color--eee, #EEE);
  d: path("M128 128h128v128H128z");
}

.x2wn8kbnc {
  fill: var(--svg-color--fff, #FFF);
  d: path("M0 0h128v128H0z");
}

</style>
