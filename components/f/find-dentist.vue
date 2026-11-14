<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhcjfccjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:find-dentist" /></template>
<style>
.dhcjfccjg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.5q0 4.811 7.72 12.53q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q7.72-7.719 7.72-12.53q0-3.417-2.416-5.834T12 1.25T6.166 3.666Q3.75 6.083 3.75 9.5m7-3.5q.68 0 1.24.457L12 6.5l.01-.043Q12.57 6 13.25 6q2.5 0 2.5 3q0 .946-.636 2.078q-.311.552-.386.854q-.007.028-.016.055l-.5 1.5q-.075.222-.262.363q-.059.044-.126.076q-.066.032-.138.051q-.071.018-.145.022t-.147-.007t-.143-.035t-.133-.062q-.064-.037-.119-.087T12.9 13.7l-.9-1.2l-.9 1.2q-.141.187-.363.262q-.07.023-.143.032t-.147.004t-.145-.025t-.137-.052t-.125-.079q-.058-.045-.107-.101q-.048-.055-.085-.12q-.036-.064-.06-.134l-.5-1.5q-.009-.027-.016-.055q-.075-.302-.386-.854Q8.25 9.946 8.25 9q0-3 2.5-3");
}

</style>
