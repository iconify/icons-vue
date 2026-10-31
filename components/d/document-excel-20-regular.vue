<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="apxtsfb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-excel-20-regular" /></template>
<style>
.apxtsfb9a {
  fill: currentColor;
  d: path("M8 9a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2zm2.586-7a1.5 1.5 0 0 1 1.06.44l3.914 3.914a1.5 1.5 0 0 1 .44 1.06V16a2 2 0 0 1-2 2h-3.769a3 3 0 0 0 .595-1H14a1 1 0 0 0 1-1V8h-3.5A1.5 1.5 0 0 1 10 6.5V3H6a1 1 0 0 0-1 1v4H4V4a2 2 0 0 1 2-2zM4.725 13.496L3.195 16H4.47l.88-1.58c.05-.101.083-.153.125-.265h.014c.032.087.054.138.115.251L6.452 16h1.352l-1.488-2.542L7.762 11h-1.27l-.783 1.408c-.069.129-.094.181-.16.318h-.015c-.047-.118-.087-.188-.146-.303L4.634 11H3.3zM11 6.5a.5.5 0 0 0 .5.5h3.293L11 3.207z");
}

</style>
