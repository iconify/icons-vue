<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwa0byb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fit-width-outline-rounded" /></template>
<style>
.cwa0byb4g {
  fill: currentColor;
  d: path("M4 19.385V4.615q0-.251.182-.433T4.615 4t.434.182t.182.434v14.769q0 .252-.182.433T4.615 20t-.433-.182T4 19.385m14.77 0V4.615q0-.251.181-.433T19.385 4t.433.182t.182.434v14.769q0 .252-.182.433t-.433.182t-.434-.182t-.182-.434m-7.203-6.95q-.182-.182-.182-.434t.182-.434t.434-.181t.434.181t.182.434t-.182.434t-.434.182t-.434-.182m-3.692 0q-.182-.182-.182-.434t.182-.434t.434-.181t.433.181t.182.434t-.182.434t-.433.182t-.434-.182m7.385 0q-.182-.182-.182-.434t.182-.434t.433-.181t.434.181t.182.434t-.182.434t-.434.182t-.433-.182");
}

</style>
