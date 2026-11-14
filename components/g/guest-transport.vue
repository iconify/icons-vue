<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0jb-j11i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guest-transport" /></template>
<style>
.f0jb-j11i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.75H6q-1.76 0-3.005 1.245T1.75 7v6q0 1.76 1.245 3.005q.78.78 1.762 1.071Q4.5 17.66 4.5 18.5q0 2.75 2.75 2.75T10 18.5q0-.719-.188-1.25h3.876q-.188.531-.188 1.25q0 2.75 2.75 2.75T19 18.5q0-.765-.213-1.317q1.262-.221 2.218-1.178Q22.25 14.76 22.25 13V7q0-1.76-1.245-3.005T18 2.75M6.75 5.5h5q.932 0 1.591.659T14 7.75v1q0 .932-.659 1.591T11.75 11h-5Q4.5 11 4.5 8.75v-1q0-2.25 2.25-2.25m10.625 0q2.125 0 2.125 2.125v4.75q0 2.125-2.125 2.125t-2.125-2.125v-4.75q0-2.125 2.125-2.125");
}

</style>
