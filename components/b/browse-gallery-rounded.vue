<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh8i9dbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:browse-gallery-rounded" /></template>
<style>
.hh8i9dbmx {
  fill: currentColor;
  d: path("M10 11.6V8q0-.425-.288-.712T9 7t-.712.288T8 8v3.975q0 .2.075.388t.225.337l2.8 2.8q.275.275.7.275t.7-.275t.275-.7t-.275-.7zm12 .4q0-1.8-.837-3.337T18.85 6.175q-.35-.225-.475-.625t.05-.775q.2-.4.6-.525t.75.1q1.95 1.225 3.088 3.25T24 12t-1.137 4.4t-3.088 3.25q-.35.225-.75.1t-.6-.525q-.175-.375-.05-.775t.475-.625q1.475-.95 2.313-2.487T22 12M5.488 20.288q-1.638-.713-2.85-1.925t-1.925-2.85T0 12t.713-3.512t1.925-2.85t2.85-1.925T9 3t3.513.713t2.85 1.924t1.924 2.85T18 12t-.712 3.513t-1.925 2.85t-2.85 1.925T9 21t-3.512-.712");
}

</style>
