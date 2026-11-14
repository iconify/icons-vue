<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6-6u7pov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dicom-image" /></template>
<style>
.p6-6u7pov {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 16.5v-.25H19q2.75 0 2.75-2.75V5q0-2.75-2.75-2.75h-8.5Q7.75 2.25 7.75 5v.25H7.5q-1.136 0-1.943.807T4.75 8v.426q-.978.292-1.755 1.069Q1.75 10.74 1.75 12.5V18q0 1.76 1.245 3.005T6 22.25h5.5q1.76 0 3.005-1.245q.777-.777 1.069-1.755H16q2.75 0 2.75-2.75M9.25 5q0-1.25 1.25-1.25H19q1.25 0 1.25 1.25v8.5q0 1.25-1.25 1.25h-.25V8q0-2.75-2.75-2.75H9.25zM7.5 6.75H16q1.25 0 1.25 1.25v8.5q0 1.25-1.25 1.25h-.25V12.5q0-1.76-1.245-3.005T11.5 8.25H6.25V8q0-.514.368-.882T7.5 6.75M5 15.25q0-3.75 3.75-3.75t3.75 3.75T8.75 19T5 15.25");
}

</style>
