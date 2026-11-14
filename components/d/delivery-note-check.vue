<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkzsnibri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delivery-note-check" /></template>
<style>
.wkzsnibri {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.761 4.258L5.084 5.376h-.001q-1.05.702-.79 1.874H4q-2.25 0-2.25 2.25V20q0 2.25 2.25 2.25h10q.932 0 1.591-.659q.553-.553.642-1.299q1.379.701 2.683-.168l.662-.441q2.672-1.781 2.672-4.993V7.606q0-1.605-1.415-2.363q-.556-.297-1.099-.34q-.026-.168-.08-.345q-.396-1.307-1.762-1.308H10.09q-1.817 0-3.329 1.008M9.75 8q2.636 0 2.956 2.316q1.544.32 1.544 2.184V18q0 2.25-2.25 2.25H6q-2.25 0-2.25-2.25v-5.5q0-1.864 1.544-2.184Q5.614 8 8.25 8zm-1.5 1.25h1.5q1.75 0 1.75 1.75t-1.75 1.75h-1.5Q6.5 12.75 6.5 11t1.75-1.75m0 1.5Q8 10.75 8 11t.25.25h1.5q.25 0 .25-.25t-.25-.25z");
}

</style>
