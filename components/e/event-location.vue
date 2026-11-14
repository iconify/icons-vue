<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4kwncchp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:event-location" /></template>
<style>
.x4kwncchp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.5q0 4.04 7.695 12.505q.024.026.05.05q.055.05.118.088q.064.038.133.063q.07.025.143.036t.147.007q.073-.003.145-.021t.139-.05q.066-.031.126-.075q.059-.044.109-.098Q20.25 13.54 20.25 9.5q0-3.417-2.416-5.834T12 1.25T6.166 3.666Q3.75 6.083 3.75 9.5m9.436-2.791l.166.335q.175.355.565.412l.368.053q.816.118 1.071.901q.254.783-.335 1.357l-.27.261q-.281.274-.214.663l.063.368q.138.811-.526 1.294q-.665.484-1.393.102l-.332-.174q-.349-.184-.698 0l-.331.174q-.729.382-1.394-.102q-.664-.483-.526-1.293l.063-.369q.067-.389-.216-.664l-.266-.259q-.591-.575-.337-1.358q.255-.783 1.069-.901l.372-.053q.388-.057.562-.411l.167-.336q.366-.735 1.186-.735t1.186.734z");
}

</style>
