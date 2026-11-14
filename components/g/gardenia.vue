<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aveogqm3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gardenia" /></template>
<style>
.aveogqm3t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.63 4.312q-1.032-.206-2.282.486q-2.613 1.447-1.391 4.173q.598 1.333 1.578 1.778q-.481.902-.225 2.244q.541 2.838 3.423 2.633q1.511-.108 2.267-.952q.756.844 2.267.952q2.882.205 3.423-2.633q.256-1.342-.225-2.244q.98-.445 1.578-1.778q1.222-2.726-1.391-4.173q-1.25-.692-2.282-.486q-.148-1.025-1.183-1.966q-2.187-1.989-4.374 0q-1.035.941-1.183 1.966M10 9q0-2 2-2t2 2t-2 2t-2-2m-6.671 8.835Q5.536 22.25 12 22.25t8.671-4.415q.067-.133.077-.282q.011-.149-.036-.29q-.048-.142-.145-.254q-.098-.113-.232-.18q-.158-.079-.335-.079q-5.594 0-8 3.307q-2.406-3.307-8-3.307q-.177 0-.335.079q-.134.067-.232.18q-.097.112-.145.254q-.047.141-.036.29q.01.149.077.282");
}

</style>
