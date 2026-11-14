<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhi61od7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cardboard-viewer" /></template>
<style>
.bhi61od7l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 4.75h15q2.75 0 2.75 2.75v9q0 2.75-2.75 2.75h-4.75q-.101 0-.199-.027q-.097-.026-.184-.078t-.157-.124q-.07-.073-.118-.162L12.805 16.5h-1.61l-1.287 2.359q-.048.089-.118.162q-.07.072-.157.124t-.184.078q-.098.027-.199.027H4.5q-2.75 0-2.75-2.75v-9q0-1.139.805-1.945q.806-.805 1.945-.805m9.878 8.372q.879.88 2.122.88t2.122-.88q.879-.879.878-2.123q.001-1.242-.878-2.121q-.879-.88-2.122-.88t-2.122.88q-.878.879-.878 2.121v.002q0 1.242.878 2.121M7.5 8q-3 0-3 3t3 3t3-3t-3-3");
}

</style>
