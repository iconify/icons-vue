<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abf5phbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:channel-manager" /></template>
<style>
.abf5phbem {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 1.75h-2.5q-2.372 0-2.493 2.25H11.5q-.09 0-.177.021t-.166.062t-.148.1q-.067.058-.119.131L7.726 8.743Q6.86 8.25 5.5 8.25q-3.75 0-3.75 3.75t3.75 3.75q1.36 0 2.226-.493l3.164 4.429q.052.073.119.131q.068.059.148.1t.166.062t.177.021h3.261q.079.876.721 1.518q.732.732 1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768t-1.768-.732h-2.5q-2.372 0-2.493 2.25h-2.871L8.79 14.166q.321-.596.418-1.416h5.549Q14.878 15 17.25 15h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768T19.75 9h-2.5q-2.372 0-2.493 2.25H9.208q-.097-.82-.418-1.416L11.886 5.5h2.871q.121 2.25 2.493 2.25h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768T19.75 1.75");
}

</style>
