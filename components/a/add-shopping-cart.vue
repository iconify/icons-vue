<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvoqh3bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-shopping-cart" /></template>
<style>
.tvoqh3bqz {
  fill: currentColor;
  d: path("M11 9V6H8V4h3V1h2v3h3v2h-3v3zM5.588 21.413Q5 20.825 5 20t.588-1.412T7 18t1.413.588T9 20t-.587 1.413T7 22t-1.412-.587m10 0Q15 20.825 15 20t.588-1.412T17 18t1.413.588T19 20t-.587 1.413T17 22t-1.412-.587M1 4V2h3.275l4.25 9h7l3.9-7H21.7l-4.4 7.95q-.275.5-.737.775T15.55 13H8.1L7 15h12v2H7q-1.125 0-1.713-.975T5.25 14.05L6.6 11.6L3 4z");
}

</style>
