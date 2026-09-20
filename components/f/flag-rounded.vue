<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l06rhevha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flag-rounded" /></template>
<style>
.l06rhevha {
  fill: currentColor;
  d: path("M7 13v7q0 .213-.144.356t-.357.144t-.356-.144T6 20V5.808q0-.343.232-.576T6.808 5h5.713q.29 0 .518.177t.284.47L13.593 7h4.6q.343 0 .575.23T19 7.8v6.4q0 .34-.232.57t-.576.23H14.48q-.29 0-.518-.177t-.284-.47L13.407 13z");
}

</style>
