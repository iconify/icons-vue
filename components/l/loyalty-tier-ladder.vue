<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq9qj2b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loyalty-tier-ladder" /></template>
<style>
.bq9qj2b7a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.168 4.05l.177.315q.169.301.508.368l.354.072q.769.154 1.011.899q.243.745-.288 1.322l-.246.266q-.234.254-.194.596l.042.36q.091.778-.543 1.24t-1.347.134l-.329-.152q-.313-.144-.627 0l-.327.151q-.714.328-1.348-.133q-.634-.462-.543-1.24l.042-.359q.04-.343-.194-.597l-.245-.265q-.532-.578-.289-1.323q.242-.745 1.01-.899l.355-.071q.339-.068.508-.369l.177-.315q.385-.683 1.168-.683t1.167.682zM4 17.75q-2.25 0-2.25 2.25T4 22.25h16q2.25 0 2.25-2.25v-6.75Q22.25 11 20 11h-4q-2.25 0-2.25 2.25v.25q0 .75-.75.75h-3q-2.25 0-2.25 2.25v.5q0 .75-.75.75z");
}

</style>
