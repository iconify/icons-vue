<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baqbav9pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:distance-rounded" /></template>
<style>
.baqbav9pm {
  fill: currentColor;
  d: path("M12 21q-2.42 0-3.96-.616q-1.54-.617-1.54-1.596q0-.436.405-.836t1.118-.693q.177-.096.388-.036q.21.06.306.237q.096.176.024.377t-.249.297q-.327.116-.625.289t-.356.346q.172.497 1.452.864T12 20t3.037-.367t1.451-.864q-.057-.173-.355-.346t-.625-.288q-.177-.096-.25-.297q-.071-.201.025-.378t.307-.237t.387.037q.713.292 1.118.692t.405.836q0 .98-1.54 1.596T12 21m-.484-3.488q-.243-.09-.455-.253q-2.546-2.08-3.803-4.058T6 9.304q0-1.564.541-2.738q.542-1.174 1.407-1.968t1.933-1.196T12 3t2.12.402q1.067.402 1.932 1.196t1.407 1.968T18 9.304q0 1.919-1.258 3.897t-3.804 4.058q-.211.162-.454.252q-.242.091-.484.091t-.485-.09M12 10.789q.671 0 1.143-.463q.472-.462.472-1.153q0-.671-.472-1.143T12 7.558q-.652 0-1.134.472t-.481 1.143q0 .69.481 1.153t1.134.463");
}

</style>
