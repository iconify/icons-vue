<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gfkqa2b0p"/><path class="i26hz5b5d"/><path class="wqjyembuf"/><path class="unx7ej2vf"/><path class="q1-l6vbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-dart" /></template>
<style>
.gfkqa2b0p {
  fill: var(--svg-color--4c6d8a, #4c6d8a);
  d: path("M27.417 5.5H18.19l-2.083 4.2H4.5v16.8h25v-21Zm0 4.2h-8.135l1.091-2.1h7.044Z");
}

.i26hz5b5d {
  fill: var(--svg-color--66c3fa, #66c3fa);
  d: path("M20.6 10a.94.94 0 0 0-.655.27l-.01.006l-6.135 3.547l6.119 6.118v.005l7.357 7.357l1.402-2.526l-5.058-12.14l-2.357-2.358a.93.93 0 0 0-.662-.277z");
}

.q1-l6vbwl {
  fill: var(--svg-color--58b6f0, #58b6f0);
  d: path("m13.826 13.839l6.263 6.262v.01l7.208 7.208l-.524 2.743h-8.114l-2.837-2.898a4.66 4.66 0 0 1-1.153-2.589h-.031z");
}

.unx7ej2vf {
  fill: var(--svg-color--235997, #235997);
  d: path("m13.78 13.804l6.26 6.266h.01l7.204 7.214l2.743-.522l.003-8.117l-2.896-2.838a4.66 4.66 0 0 0-2.588-1.154v-.032z");
}

.wqjyembuf {
  fill: var(--svg-color--215896, #215896);
  d: path("m13.822 13.795l-3.545 6.13l-.007.009a.94.94 0 0 0-.27.656a.93.93 0 0 0 .276.66l2.938 2.938l11.489 4.52l2.597-1.444l-.071-.071h-.018l-7.202-7.214H20z");
}

</style>
