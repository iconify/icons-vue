<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2bozny1q"/><path class="depup0b3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eco-bus" /></template>
<style>
.d2bozny1q {
  d: path("M14.3 15.5H2.5v-12h19v8.2");
}

.depup0b3x {
  d: path("M5.5 6.5h13V10h-13Zm-2 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.435-1.077q-.068-.106-.148-.202t-.172-.182q-.091-.086-.193-.16q-.101-.073-.211-.133t-.227-.106t-.238-.078q-.122-.031-.246-.046q-.125-.016-.25-.016q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194t-.01.196t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01q.265 0 .521-.069q.257-.069.486-.203M16 21c0-4.25 1.75-6.5 5.5-6.5c0 4.25-1.75 6.5-5.5 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
