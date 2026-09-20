<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhrpib98q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-supervised-outline-rounded" /></template>
<style>
.yhrpib98q {
  fill: currentColor;
  d: path("M14.885 19q-.214 0-.357-.143q-.144-.143-.144-.357q0-.621.87-1.06q.869-.44 2.438-.44t2.439.44T21 18.5q0 .214-.143.357T20.5 19zm1.741-4.049q-.434-.434-.434-1.066t.434-1.067t1.066-.433t1.067.433t.433 1.067t-.433 1.066t-1.067.434t-1.066-.434M4 18V6v4.435V10zm.616 1q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.31q.323 0 .628.13q.305.132.522.349L11.596 7h7.789q.69 0 1.153.463T21 8.616v2.019q0 .213-.143.356t-.357.144t-.357-.144t-.143-.356v-2.02q0-.269-.173-.442T19.385 8h-8.19l-2-2h-4.58q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173h7.173q.213 0 .356.143t.144.357t-.144.357t-.356.143z");
}

</style>
