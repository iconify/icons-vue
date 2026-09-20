<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shbkojeqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-recirculate-sharp" /></template>
<style>
.shbkojeqy {
  fill: currentColor;
  d: path("M6.75 19q-.89 0-1.606-.518q-.715-.518-1.121-1.328H1v-6.558h2.73L5.617 5.5h8.98l1.214 1.971l-1.88 2.202h-1.516L10 7.26L5.26 12L10 16.74l2.414-2.413h3.65l3.463-4.056l3.473.287v6.596h-3.042q-.387.81-1.102 1.328T17.25 19t-1.606-.518t-1.121-1.328H9.458q-.387.81-1.102 1.328T6.75 19M10 14.058l.627-.608l-1.002-1.008h5.566l5.936-6.923l-.663-.577l-5.68 6.616H9.626l1.002-1.008L10 9.942L7.942 12z");
}

</style>
