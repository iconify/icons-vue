<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw1oitp5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flights-and-hotels-outline-sharp" /></template>
<style>
.cw1oitp5k {
  fill: currentColor;
  d: path("M7.588 14.588Q8.175 14 9 14t1.413.588T11 16t-.587 1.413T9 18t-1.412-.587T7 16t.588-1.412M12 14h8v9h-2v-2H6v2H4V13h2v6h6zm3.75-1L12.8 7.65l-2.65 2.65l.25 1.7l-.75.75l-1.175-2.2l-2.2-1.2l.75-.75l1.7.225l2.65-2.65L6 3.25l.95-.95l6.6 1.7l2.7-2.7q.3-.3.725-.3t.725.3t.3.725t-.3.725L15 5.45l1.7 6.6zM18 19v-3h-4v3zm-4 0v-3z");
}

</style>
