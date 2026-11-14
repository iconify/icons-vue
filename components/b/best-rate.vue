<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxilww8yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:best-rate" /></template>
<style>
.lxilww8yn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.362 9.82L6.64 5.946Q7.652 4.75 9.217 4.75h9.658q3.375 0 3.375 3.375v7.75q0 3.375-3.375 3.375H9.217q-1.565 0-2.575-1.194l-3.28-3.876q-1.845-2.18 0-4.36m13.324-.611q-.366-.734-1.186-.734t-1.186.735l-.167.336q-.174.354-.562.411l-.372.053q-.814.118-1.069.901q-.254.783.337 1.358l.266.259q.283.275.216.664l-.063.369q-.138.81.526 1.293q.665.484 1.394.102l.331-.174q.349-.184.698 0l.332.175q.728.381 1.393-.103q.664-.483.526-1.294l-.063-.368q-.067-.389.214-.663l.27-.261q.589-.574.335-1.357q-.255-.783-1.071-.901l-.368-.053q-.39-.057-.565-.412zM7.5 9.75q-2.25 0-2.25 2.25t2.25 2.25T9.75 12T7.5 9.75");
}

</style>
