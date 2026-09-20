<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8yvu7bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-check-2" /></template>
<style>
.v8yvu7bvi {
  fill: currentColor;
  d: path("M21.538 14.463Q23 15.925 23 18t-1.463 3.538T18 23t-3.537-1.463T13 18t1.463-3.537T18 13t3.538 1.463M11 18q0 .525.075 1.025T11.3 20H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h6l2 2h8q.825 0 1.413.588T22 8v4.275q-.875-.625-1.9-.95T18 11q-2.9 0-4.95 2.05T11 18m6.275 2.25l3.475-3.45l-1.05-1.05l-2.425 2.375l-.975-.975l-1.05 1.075z");
}

</style>
