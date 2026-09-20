<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs483f13h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flights-and-hotels" /></template>
<style>
.zs483f13h {
  fill: currentColor;
  d: path("M7.934 15.434Q8.367 15 9 15t1.066.434t.434 1.066t-.434 1.066Q9.633 18 9 18t-1.066-.434Q7.5 17.133 7.5 16.5t.434-1.066M12 15h5.385q.69 0 1.152.463T19 16.616V22.5h-1V20H6v2.5H5V14h1v5h6zm3.75-2L12.8 7.65l-2.65 2.65l.27 1.72l-.75.75l-1.214-2.2l-2.22-1.2l.75-.75l1.72.224l2.669-2.669L6 3.25l.95-.95l6.6 1.7l2.7-2.7q.3-.3.725-.3t.725.3t.3.725t-.3.725L15 5.45l1.7 6.6z");
}

</style>
