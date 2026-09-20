<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roz9yq3qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:inactive-order-sharp" /></template>
<style>
.roz9yq3qo {
  fill: currentColor;
  d: path("M16.558 19.75h.769v-3.27h-.77zm2.115 0h.77v-3.27h-.77zM6.769 8.73h10.462v-1H6.769zM18 22.117q-1.671 0-2.835-1.165Q14 19.787 14 18.116t1.165-2.836T18 14.116t2.836 1.164T22 18.116q0 1.67-1.164 2.835Q19.67 22.116 18 22.116M4 20.769V4h16v7.56q-.892-.293-1.828-.301t-1.845.241H6.769v1h7.312q-.752.521-1.326 1.223t-.946 1.546H6.77v1h4.71q-.108.404-.168.815t-.061.858q0 .685.143 1.359t.43 1.299l-.034.034l-1.135-.826l-1.346.961l-1.346-.961l-1.346.961l-1.347-.961z");
}

</style>
