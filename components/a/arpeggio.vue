<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv-e0dcgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arpeggio" /></template>
<style>
.kv-e0dcgz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 5.25q0-1.459-1.498-2.807q-.111-.1-.252-.15q-.14-.05-.289-.042t-.284.072t-.234.175q-.05.055-.088.119q-.037.063-.062.133q-.025.069-.035.143t-.007.146q.004.074.022.146q.018.071.05.138t.076.126t.099.108Q7.5 4.459 7.5 5.25T6.498 6.943Q5 8.291 5 9.75t1.498 2.807Q7.5 13.459 7.5 14.25t-1.002 1.693Q5 17.291 5 18.75t1.498 2.807q.111.1.252.15q.14.05.289.042t.284-.072t.234-.175q.05-.055.088-.119q.037-.063.062-.133q.025-.069.035-.143t.007-.146q-.004-.074-.022-.146q-.018-.071-.05-.138t-.076-.126t-.099-.108Q6.5 19.541 6.5 18.75t1.002-1.693Q9 15.709 9 14.25t-1.498-2.807Q6.5 10.541 6.5 9.75t1.002-1.693Q9 6.709 9 5.25M11.5 5q0-2.5 3.5-2.5T18.5 5T15 7.5T11.5 5M15 9.5q-3.5 0-3.5 2.5t3.5 2.5t3.5-2.5T15 9.5M11.5 19q0-2.5 3.5-2.5t3.5 2.5t-3.5 2.5t-3.5-2.5");
}

</style>
