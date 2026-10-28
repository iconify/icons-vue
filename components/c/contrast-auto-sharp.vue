<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptkv4mauj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contrast-auto-sharp" /></template>
<style>
.ptkv4mauj {
  fill: currentColor;
  d: path("M12 21q-1.864 0-3.506-.71q-1.642-.711-2.857-1.926q-1.216-1.216-1.926-2.858Q3 13.864 3 12q0-1.767.643-3.342t1.753-2.771t2.618-1.955t3.236-.893h.023q-.61.834-.941 1.843T10 7q0 1.627.668 3.012q.669 1.384 1.832 2.334v7.637q2.766-.177 4.826-2.019q2.06-1.841 2.549-4.589q.292-.14.56-.291t.527-.357q-.135 1.729-.894 3.24q-.758 1.51-1.954 2.625q-1.197 1.116-2.772 1.762T12 21m1.377-10l3.47-9h.73l3.508 9H20.03l-1.008-2.539H15.4L14.392 11zm2.32-3.35h3.03l-1.496-3.996h-.077z");
}

</style>
