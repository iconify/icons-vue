<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmiyy2mds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lawn-bowls" /></template>
<style>
.gmiyy2mds {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 6q0-2.75 2.75-2.75T14.75 6T12 8.75T9.25 6m-7.5 9q0-1.968 1.391-3.359T6.5 10.25t3.359 1.391T11.25 15t-1.391 3.359T6.5 19.75t-3.359-1.391T1.75 15m12.391-3.359Q12.75 13.032 12.75 15t1.391 3.359T17.5 19.75t3.359-1.391T22.25 15t-1.391-3.359T17.5 10.25t-3.359 1.391M6.5 13q-2 0-2 2t2 2q.828 0 1.414-.586T8.5 15t-.586-1.414T6.5 13m9 2q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
