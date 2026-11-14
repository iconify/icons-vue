<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0z6nyn4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:figure-eight-knot" /></template>
<style>
.g0z6nyn4n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.247 6.869Q14.97 9.773 13.026 12q2.095 2.401 2.254 5.588q.088 1.745-.654 2.846Q13.741 21.75 12 21.75t-2.626-1.316q-.417-.619-.572-1.441L5.46 21.592q-.058.045-.124.078q-.066.034-.137.053q-.071.02-.145.025t-.147-.004t-.143-.032q-.071-.024-.135-.06q-.064-.037-.12-.085t-.101-.107q-.092-.117-.131-.261t-.021-.292t.092-.278t.192-.221l4.213-3.277Q9.03 14.227 10.974 12Q8.879 9.599 8.72 6.412q-.088-1.745.654-2.846Q10.259 2.25 12 2.25t2.626 1.316q.417.619.572 1.441l3.342-2.599q.117-.092.261-.131t.292-.021t.278.092t.221.192q.045.058.078.124q.034.066.053.137q.02.071.025.145t-.004.147t-.032.143q-.024.071-.06.135q-.037.064-.085.12t-.107.101z");
}

</style>
