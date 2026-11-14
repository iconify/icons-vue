<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="go68hwb3q"/><path class="h2y9x3b1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drive-through-lane" /></template>
<style>
.go68hwb3q {
  d: path("M13.746 12.5H2.5v-3l2-1l2.5-4h6l2.788 3.718");
}

.h2y9x3b1x {
  d: path("M3.5 14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.244-.978q-.065-.116-.144-.222q-.08-.106-.173-.201t-.197-.176q-.105-.082-.219-.149q-.115-.067-.237-.118q-.122-.052-.25-.086q-.128-.035-.26-.052q-.131-.018-.264-.018q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T10 14.5t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01q.132 0 .262-.017q.131-.018.258-.052t.249-.085q.121-.05.235-.116t.218-.147q.104-.08.197-.174t.173-.198t.145-.219M16.5 11h5v5.5h-5Zm2.5 5.5v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
