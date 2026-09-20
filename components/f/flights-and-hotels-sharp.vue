<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq2ga0h-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flights-and-hotels-sharp" /></template>
<style>
.fq2ga0h-o {
  fill: currentColor;
  d: path("M7.934 17.566Q7.5 17.133 7.5 16.5t.434-1.066T9 15t1.066.434q.434.433.434 1.066t-.434 1.066Q9.633 18 9 18t-1.066-.434M5 22.5V14h1v5h6v-4h7v7.5h-1V20H6v2.5zM15.75 13L12.8 7.65l-2.65 2.65l.27 1.72l-.75.75l-1.214-2.2l-2.22-1.2l.75-.75l1.72.224l2.669-2.669L6 3.25l.95-.95l6.6 1.7l2.7-2.7q.3-.3.725-.3t.725.3t.3.725t-.3.725L15 5.45l1.7 6.6z");
}

</style>
