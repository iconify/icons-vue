<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r73ftwg9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eyebrow-stencil" /></template>
<style>
.r73ftwg9w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 4.25H6q-1.76 0-3.005 1.245T1.75 8.5v7q0 1.76 1.245 3.005T6 19.75h12q1.76 0 3.005-1.245T22.25 15.5v-7q0-1.76-1.245-3.005T18 4.25M5.283 14.279q1.595-5.183 6.254-6.139q4.571-.937 7.555 2.9q.045.058.078.124q.034.066.053.137q.02.071.025.145t-.004.147t-.032.143q-.024.071-.06.135q-.037.064-.085.12t-.107.101q-.117.092-.261.131t-.292.021q-7.525-.94-11.919 2.825q-.113.098-.255.144t-.291.035q-.148-.012-.281-.079q-.133-.068-.23-.181q-.062-.072-.104-.157t-.061-.178t-.015-.188t.032-.186");
}

</style>
