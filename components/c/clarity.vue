<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmx1f0bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:clarity" /></template>
<style>
.rmx1f0bih {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.293 10.233l-6.526-6.526v-.001Q12 1.941 10.233 3.707L8.91 5.03q1.062-1.062 2.45-.488q1.39.575 1.39 2.079v10.758q0 1.504-1.39 2.079t-2.451-.489l1.324 1.325q1.767 1.765 3.534-.001l6.527-6.526q1.765-1.767-.001-3.534M3.045 12.885q-.174-.407-.174-.885t.174-.885q-.443.885 0 1.77");
}

</style>
