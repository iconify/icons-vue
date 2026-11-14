<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt5vlib6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-ai" /></template>
<style>
.wt5vlib6o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 2.25h15q2.75 0 2.75 2.75v10.5q0 2.75-2.75 2.75h-8.743L6.46 21.592q-.058.045-.124.078q-.066.034-.137.053q-.071.02-.145.025t-.147-.004t-.143-.032q-.071-.024-.135-.06q-.064-.037-.12-.085t-.101-.107q-.077-.098-.117-.217q-.041-.118-.041-.243v-2.75H4.5q-2.75 0-2.75-2.75V5q0-1.139.805-1.945q.806-.805 1.945-.805m8.25 5.5V6q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 5.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 6v1.75H9.625q-1.398 0-2.386.989q-.989.988-.989 2.386v.75q0 3.375 3.375 3.375h4.75q3.375 0 3.375-3.375v-.75q0-3.375-3.375-3.375z");
}

</style>
