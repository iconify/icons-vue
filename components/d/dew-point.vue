<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlizo3bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dew-point" /></template>
<style>
.xlizo3bgb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.95 1.99q.019-.021.04-.04q.109-.101.249-.153t.289-.046q.149.005.284.067q.136.062.238.172q5.341 5.752 6.424 10.283q-2.724.251-2.724 3.227v1.36q-.793.91-.964 2.206q-.129.983.145 1.843q-1.542.841-3.431.841q-3.003 0-5.127-2.123T3.25 14.5q0-5.295 6.7-12.51m5.076 17.239q.149-1.135.974-1.849V15.5q0-2 2-2t2 2v1.88q.825.714.974 1.849q.178 1.348-.718 2.37q-.897 1.022-2.256 1.022t-2.256-1.022t-.718-2.37M17.5 17.75q0 .093-.022.182q-.023.09-.067.172q-.043.081-.105.15t-.139.12q-.565.377-.654 1.051t.359 1.185t1.128.511t1.128-.511t.359-1.185t-.654-1.051q-.077-.052-.139-.12q-.062-.069-.105-.15q-.044-.082-.067-.172q-.022-.089-.022-.182V15.5q0-.5-.5-.5t-.5.5z");
}

</style>
