<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i-w1j6b1w"/><path class="q4dvkc--n"/><path class="kns8wvxzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-estonia" /></template>
<style>
.i-w1j6b1w {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.kns8wvxzb {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M60.3 42c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10H3.7C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10z");
}

.q4dvkc--n {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2");
}

</style>
