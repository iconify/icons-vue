<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q062cubgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:footsteps" /></template>
<style>
.q062cubgq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.779 3.222Q12.75 4.593 12.75 6.5t1.029 3.278q1.103 1.472 2.721 1.472t2.721-1.472Q20.25 8.407 20.25 6.5t-1.029-3.278Q18.118 1.75 16.5 1.75t-2.721 1.472m-9 5.5Q3.75 10.093 3.75 12t1.029 3.278Q5.882 16.75 7.5 16.75t2.721-1.472Q11.25 13.907 11.25 12t-1.029-3.278Q9.118 7.25 7.5 7.25T4.779 8.722m8.971 6.028q0-2 2.75-2t2.75 2t-2.75 2t-2.75-2m-9 5.5q0-2 2.75-2t2.75 2t-2.75 2t-2.75-2");
}

</style>
