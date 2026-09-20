<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgol0fh8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hvac-rounded" /></template>
<style>
.tgol0fh8o {
  fill: currentColor;
  d: path("M15.616 15.616q1.48-1.481 1.48-3.616t-1.48-3.616T12 6.904t-3.616 1.48Q6.904 9.866 6.904 12t1.48 3.616q1.481 1.48 3.616 1.48t3.616-1.48m-5.199.17q-.742-.33-1.35-.901h5.866q-.608.57-1.35.9t-1.583.33t-1.583-.33m-1.944-1.67q-.22-.407-.364-.84t-.194-.89h8.17q-.05.457-.195.89q-.144.433-.382.84zm-.558-2.5q.05-.457.194-.89t.383-.84h7.035q.22.407.363.84q.144.433.194.89zm1.152-2.5q.608-.57 1.35-.9T12 7.885t1.583.33t1.35.9zM5.616 20q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h12.769q.67 0 1.143.472q.472.472.472 1.144v12.769q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
