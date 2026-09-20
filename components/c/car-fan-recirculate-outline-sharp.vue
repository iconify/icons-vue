<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4gga3b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-recirculate-outline-sharp" /></template>
<style>
.s4gga3b8q {
  fill: currentColor;
  d: path("M6.75 19q-.89 0-1.606-.518q-.715-.518-1.121-1.328H1v-6.558h2.73L5.617 5.5h8.98l1.214 1.971l-.683.792l-1.08-1.763H6.342L4.44 11.596H2v4.558h2.866v.135q0 .682.552 1.197Q5.971 18 6.75 18t1.332-.514q.552-.515.552-1.197v-.135h6.732v.135q0 .682.552 1.197q.553.514 1.332.514q.798 0 1.341-.514q.543-.515.543-1.197v-.135H22v-4.67l-3.284-.267l.811-.946l3.473.287v6.596h-3.042q-.387.81-1.102 1.328T17.25 19t-1.606-.518t-1.121-1.328H9.458q-.387.81-1.102 1.328T6.75 19M10 14.058l.627-.608l-1.002-1.008h5.566l5.936-6.923l-.663-.577l-5.68 6.616H9.626l1.002-1.008L10 9.942L7.942 12z");
}

</style>
