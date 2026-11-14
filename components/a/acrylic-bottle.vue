<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlep_botw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:acrylic-bottle" /></template>
<style>
.qlep_botw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 1.75h4.5q2.5 0 2.5 2.5q0 1.036-.732 1.768q-.35.349-.768.532v.95q0 .263 1.097 1.027Q18.75 10.2 18.75 12v7.5q0 2.75-2.75 2.75H8q-2.75 0-2.75-2.75V12q0-1.8 2.403-3.473Q8.75 7.763 8.75 7.5v-.95q-.418-.183-.768-.532q-.732-.732-.732-1.768q0-2.5 2.5-2.5m.5 5v.75q0 1.046-1.74 2.258Q6.75 10.983 6.75 12v1.375q2.793-.942 5.585.454q2.458 1.229 4.915.191V12q0-1.017-1.76-2.242q-1.74-1.212-1.74-2.258v-.75zm7 8.875q-2.793.942-5.585-.454q-2.458-1.229-4.915-.191v4.52q0 1.25 1.25 1.25h8q1.25 0 1.25-1.25z");
}

</style>
