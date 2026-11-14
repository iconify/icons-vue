<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kouit415i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-collectibles" /></template>
<style>
.kouit415i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.728 21.282l-3.535.943q-.071.019-.145.023q-.074.005-.147-.005q-.073-.009-.143-.033t-.134-.061t-.119-.086q-.056-.048-.101-.107q-.044-.059-.077-.125t-.052-.138l-.001-.005l-3.75-14.5q-.019-.072-.023-.145q-.004-.074.006-.147t.035-.142q.024-.07.061-.134q.038-.063.086-.118q.049-.055.108-.1q.059-.044.125-.077q.067-.032.138-.051l10.5-2.75q.071-.018.144-.023q.073-.004.146.006t.142.033q.07.024.133.061q.064.036.119.085q.055.048.1.106t.078.124t.052.137l.599 2.197h4.552q1.398 0 2.386.989q.989.988.989 2.386v9.25q0 1.398-.989 2.386q-.988.989-2.386.989h-6.25q-1.807 0-2.647-.968m-.636-1.383Q9 19.433 9 18.875v-9.25Q9 6.25 12.375 6.25h.143l-.296-1.086l-9.059 2.372l3.374 13.045z");
}

</style>
