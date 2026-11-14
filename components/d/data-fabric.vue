<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygljjbbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-fabric" /></template>
<style>
.ygljjbbda {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.25q-2.5 0-2.5 2.5q0 .72.207 1.232L4.911 9.778Q4.388 9.5 3.75 9.5q-2.5 0-2.5 2.5t2.5 2.5q.638 0 1.161-.278l4.796 4.796Q9.5 19.53 9.5 20.25q0 2.5 2.5 2.5q1.036 0 1.768-.732t.732-1.768q0-.638-.278-1.161l4.796-4.796q.512.207 1.232.207q1.036 0 1.768-.732T22.75 12t-.732-1.768T20.25 9.5q-.72 0-1.232.207l-4.796-4.796q.278-.523.278-1.161q0-1.036-.732-1.768T12 1.25m-1.232 4.793q.222.089.482.14v2.871q-1.902.294-2.196 2.196H6.142q-.065-.214-.17-.411zm1.982.099q.214-.065.411-.17l4.796 4.796q-.089.222-.14.482h-2.871q-.294-1.902-2.196-2.196zm2.196 6.608h2.871q.051.26.14.482l-4.796 4.796q-.197-.105-.411-.17v-2.912q1.902-.294 2.196-2.196m-3.696 5.067q-.26.051-.482.14l-4.796-4.796q.105-.197.17-.411h2.912q.294 1.902 2.196 2.196z");
}

</style>
