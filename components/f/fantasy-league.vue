<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm1s3dued"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fantasy-league" /></template>
<style>
.lm1s3dued {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.321 14.21q-.181-.065-.356-.143t-.344-.169q-.169-.092-.331-.196q-.161-.104-.314-.22t-.296-.244t-.277-.265q-.134-.139-.256-.287q-.123-.148-.233-.304q-.111-.157-.209-.322t-.184-.337q-.085-.172-.157-.35t-.13-.362t-.102-.37t-.073-.376q-.03-.19-.044-.382Q7 9.692 7 9.5v-6h10v5.8M7 5.5H5a2 2 0 0 0 0 4h2m10-4h2q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132q.07.069.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T21 7.5q0 .098-.01.196q-.009.098-.028.194q-.02.097-.048.191q-.029.094-.066.184q-.038.091-.084.178q-.046.086-.101.168t-.117.158t-.132.145t-.145.132t-.158.117t-.168.101q-.087.046-.178.084q-.09.037-.184.066q-.094.028-.191.048q-.096.019-.194.028T19 9.5h-.343M12 17.9V20m-4 0h4.9m4.85-6l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
