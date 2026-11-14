<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp5p8dbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bathroom-mirror-light" /></template>
<style>
.sp5p8dbup {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 3.25q0-2 2-2q.828 0 1.414.586T8.5 3.25t-.586 1.414T6.5 5.25q-2 0-2-2m7.5-2q-2 0-2 2t2 2t2-2t-2-2m3.5 2q0-2 2-2t2 2t-2 2t-2-2M7.521 9.087Q5.75 11.341 5.75 14.5t1.771 5.413Q9.357 22.25 12 22.25t4.479-2.337q1.771-2.254 1.771-5.413t-1.771-5.413Q14.643 6.75 12 6.75T7.521 9.087");
}

</style>
