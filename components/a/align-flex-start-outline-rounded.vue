<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rodkdwb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-flex-start-outline-rounded" /></template>
<style>
.rodkdwb-g {
  fill: currentColor;
  d: path("M3.5 4q-.213 0-.356-.144T3 3.499t.144-.356T3.5 3h17q.213 0 .356.144t.144.357t-.144.356T20.5 4zm8.308 16q-.343 0-.576-.232T11 19.192V7.808q0-.343.232-.576T11.808 7h.384q.344 0 .576.232t.232.576v11.384q0 .344-.232.576t-.576.232z");
}

</style>
