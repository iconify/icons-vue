<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwfkzgb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:climbing-hold" /></template>
<style>
.uwfkzgb6i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 1.75q2.25 0 2.25 2.25v1.448q6.248-1.959 10.929 1.436q3.097 2.072 3.442 5.286q.353 3.296-2.414 5.424l-.03.023q-4.334 3-11.927.887V20q0 2.25-2.25 2.25T2.25 20V4q0-.932.659-1.591T4.5 1.75m2.25 15.194q7.192 2.112 11.058-.55q2.084-1.613 1.821-4.064q-.27-2.523-2.795-4.206l-.025-.017Q12.577 5.029 6.75 7.027zM10.25 12q0-2.5 2.5-2.5q1.036 0 1.768.732T15.25 12t-.732 1.768t-1.768.732q-2.5 0-2.5-2.5");
}

</style>
