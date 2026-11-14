<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwojc9jsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delivery-pickup-in-store" /></template>
<style>
.wwojc9jsq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.311 6.205q-.061.141-.061.295q.001 2.597 2.25 2.945v7.836q-1.75.235-1.75 2.219q0 2.25 2.25 2.25h14q2.25 0 2.25-2.25q0-1.984-1.75-2.219V9.445q2.248-.348 2.25-2.944v-.022zM8.914 17.25H6V9.445q.951-.147 1.499-.696q.75.751 2.251.751T12 8.75q.75.75 2.25.75t2.251-.751q.549.548 1.499.696v7.805h-2.913q.663-.615.663-1.612v-1.776q0-.301-.06-.567q.021-.051.035-.104q.038-.144.018-.292t-.095-.277q-.044-.075-.103-.137q-.06-.063-.132-.111t-.153-.078t-.167-.04q-.2-.186-.459-.338l-1.5-.875q-1.134-.661-2.268 0l-1.5.875q-.26.152-.459.338q-.086.01-.167.04t-.153.078t-.132.111t-.103.137q-.075.129-.095.277t.018.292q.014.053.035.104q-.06.266-.06.567v1.776q0 .996.664 1.612");
}

</style>
