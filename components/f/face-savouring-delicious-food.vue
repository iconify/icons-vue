<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qgsyt7yth"/><path class="n_gsbl3dr"/><path class="qqcawk-6w"/><path class="rb8s0lbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-savouring-delicious-food" /></template>
<style>
.n_gsbl3dr {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M42 47.9c-5-5-2.8-2.8 2.5-8.1s3.1-7.6 8.1-2.5c5 5 5.2 9.9 2.2 12.9c-2.9 2.9-7.8 2.7-12.8-2.3");
}

.qgsyt7yth {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("M62 32c0 16.6-13.4 30-30 30S2 48.6 2 32S15.4 2 32 2s30 13.4 30 30");
}

.qqcawk-6w {
  fill: var(--svg-color--e2596c, #e2596c);
  d: path("m45.6 38.7l6.8 9l-8.9-6.8z");
}

.rb8s0lbml {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M28.5 24.9c-1.9-5.1-4.7-7.7-7.5-7.7s-5.6 2.6-7.5 7.7c-.2.5.8 1.4 1.3.9c1.8-1.9 4-2.7 6.2-2.7s4.4.8 6.2 2.7c.6.5 1.5-.4 1.3-.9m21.9 0c-1.9-5.1-4.7-7.7-7.5-7.7s-5.6 2.6-7.5 7.7c-.2.5.8 1.4 1.3.9c1.8-1.9 4-2.7 6.2-2.7s4.4.8 6.2 2.7c.5.5 1.5-.4 1.3-.9M48.1 33c-4.3 6.1-9.5 7.6-16.1 7.6S20.2 39.1 15.9 33c-.6-.8-2.2-.3-1.8.9c2.3 8 10 12.7 18 12.7s15.7-4.7 18-12.7c.2-1.2-1.4-1.7-2-.9");
}

</style>
