<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="colmd-bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:co-present-outline-sharp" /></template>
<style>
.colmd-bur {
  fill: currentColor;
  d: path("M21 19.577V4.5H3v8H2v-9h20v16.077zm-14.123-7.07Q6 11.632 6 10.386t.877-2.123Q7.754 7.385 9 7.385t2.123.877t.877 2.123t-.877 2.123T9 13.385t-2.123-.877m3.536-.711Q11 11.21 11 10.385t-.587-1.413T9 8.385t-1.412.587T7 10.385t.588 1.412T9 12.385t1.413-.588M2 20.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v1.646zm1-1h12v-.647q0-.332-.215-.625q-.214-.292-.593-.494q-1.234-.598-2.545-.916T9 16.615t-2.646.319t-2.546.916q-.38.202-.593.494Q3 18.637 3 18.97zm6 0");
}

</style>
