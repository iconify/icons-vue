<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p830clbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:button-deck" /></template>
<style>
.p830clbhy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 3.25h10.25q2.123 0 3.624 1.501t1.501 3.624v7.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 15.625v-7.25q0-2.123 1.501-3.624T6.875 3.25M8 6H7Q4.5 6 4.5 8.5T7 11h1q2.5 0 2.5-2.5T8 6m8 0q-2.5 0-2.5 2.5T16 11h1q2.5 0 2.5-2.5T17 6zm-8 7H7q-2.5 0-2.5 2.5T7 18h1q2.5 0 2.5-2.5T8 13m8 0q-2.5 0-2.5 2.5T16 18h1q2.5 0 2.5-2.5T17 13z");
}

</style>
