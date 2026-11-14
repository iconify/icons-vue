<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnbxs0bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:broadcast-tower-off" /></template>
<style>
.bnbxs0bmf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.383 8.463q.084-.016.167-.04t.164-.055q.08-.03.158-.068q.077-.038.151-.082t.144-.094t.136-.107q.065-.056.126-.117q.06-.062.115-.128q.054-.067.103-.138t.092-.146q.042-.075.078-.153t.065-.159t.052-.165t.036-.168t.023-.171Q14 6.586 14 6.5q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145q-.069-.07-.145-.132t-.158-.117t-.168-.101t-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T12 4.5q-.085 0-.169.007q-.085.007-.168.022q-.084.014-.166.035t-.162.05q-.08.028-.157.063t-.151.076t-.145.089t-.136.1t-.127.112q-.062.058-.118.122q-.056.063-.107.131t-.095.141t-.083.147q-.038.076-.07.154q-.032.079-.057.16t-.043.164M6.5 21.5l3.273-7.736M16 3.5a4.5 4.5 0 0 1 0 6m3-7a8 8 0 0 1 0 8m-11-7q-.127.142-.241.293M4.07 7.997q.253 1.33.93 2.503m-1.5-7l17 17");
}

</style>
