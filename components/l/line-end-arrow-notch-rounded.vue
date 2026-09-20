<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6d5-lt8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-arrow-notch-rounded" /></template>
<style>
.s6d5-lt8d {
  fill: currentColor;
  d: path("M12.7 17.925q-.35.2-.625-.062T12 17.25L14.425 13H3q-.425 0-.712-.288T2 12t.288-.712T3 11h11.425L12 6.75q-.2-.35.075-.612t.625-.063l7.975 5.075q.475.3.475.85t-.475.85z");
}

</style>
