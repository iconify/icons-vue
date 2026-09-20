<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvxqsjbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:expand-circle-down-rounded" /></template>
<style>
.vvxqsjbwu {
  fill: currentColor;
  d: path("M12 12.675L9.625 10.3q-.275-.275-.687-.275t-.713.275q-.3.3-.3.713t.3.712L11.3 14.8q.3.3.7.3t.7-.3l3.1-3.1q.3-.3.287-.7t-.312-.7q-.3-.275-.7-.288t-.7.288zM12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
