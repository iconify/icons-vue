<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfcz_p8ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:light-group-2-outline-sharp" /></template>
<style>
.dfcz_p8ed {
  fill: currentColor;
  d: path("m2.939 21l3.715-9.098V8.731H2.173L5.5 3h3.327l3.327 5.73h-4.5v3.172L11.358 21h-1.073l-2.637-6.396V21h-1v-6.396L4.012 21zm13.867-3.384q-1.22 0-2.102-.787q-.883-.787-1.098-2.002H11.5q0-1.316.663-2.459t1.766-1.922q.106-.987.762-1.72q.655-.734 1.636-.886V3h1v4.84q.956.152 1.622.886t.79 1.72q1.084.779 1.759 1.922t.675 2.459h-2.15q-.234 1.215-1.127 2.002q-.892.787-2.09.787m-4.146-3.789h8.31q-.097-.754-.574-1.345T19.3 11.423l-.538-.39l-.062-.625q-.088-.69-.626-1.165t-1.247-.474q-.71 0-1.253.465t-.607 1.155l-.08.644l-.514.37q-.638.468-1.13 1.069q-.493.601-.583 1.355M3.892 7.731h6.543L8.248 4H6.073zm12.921 8.865q.75 0 1.326-.503q.575-.502.85-1.266h-4.33q.237.764.803 1.266q.565.503 1.351.503m-9.66-8.865");
}

</style>
