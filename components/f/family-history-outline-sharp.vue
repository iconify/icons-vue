<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjup8fbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:family-history-outline-sharp" /></template>
<style>
.zjup8fbdw {
  fill: currentColor;
  d: path("M9.76 20.412q-.914-.914-.914-2.239q0-1.184.756-2.057q.756-.872 1.898-1.049V12.5H6V8.904H3.596V3.096h5.808v5.808H7V11.5h10V8.856q-1.142-.177-1.898-1.05q-.756-.871-.756-2.056q0-1.324.915-2.24q.915-.914 2.24-.914t2.238.915t.915 2.239q0 1.185-.756 2.057T18 8.856V12.5h-5.5v2.567q1.142.177 1.898 1.05q.756.872.756 2.056q0 1.325-.915 2.24q-.915.914-2.24.914t-2.238-.915m9.265-13.14q.628-.632.628-1.526t-.632-1.522t-1.526-.628t-1.522.632t-.628 1.526t.632 1.522t1.526.628t1.522-.632m-14.43.632h3.808V4.096H4.596zm8.93 11.791q.628-.632.628-1.526t-.632-1.522t-1.526-.628t-1.522.632t-.628 1.526t.632 1.522t1.526.628t1.522-.632M12 18.173");
}

</style>
