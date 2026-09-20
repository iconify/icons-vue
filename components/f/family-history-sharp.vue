<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx4s3bcgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:family-history-sharp" /></template>
<style>
.tx4s3bcgt {
  fill: currentColor;
  d: path("M9.76 20.413q-.914-.915-.914-2.24q0-1.184.756-2.057q.756-.872 1.898-1.049V12.5H6V8.904H3.596V3.096h5.808v5.808H7V11.5h10V8.856q-1.142-.177-1.898-1.05q-.756-.871-.756-2.056q0-1.325.914-2.24q.915-.914 2.24-.914t2.24.914t.914 2.24q0 1.185-.756 2.057T18 8.856V12.5h-5.5v2.567q1.142.177 1.898 1.05q.756.872.756 2.056q0 1.325-.914 2.24q-.915.914-2.24.914t-2.24-.914");
}

</style>
