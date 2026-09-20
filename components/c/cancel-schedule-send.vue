<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkw5nmbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cancel-schedule-send" /></template>
<style>
.lkw5nmbzh {
  fill: currentColor;
  d: path("m15.225 19.475l1.75-1.75l1.75 1.75l.75-.75L17.75 17l1.75-1.75l-.75-.75L17 16.25l-1.75-1.75l-.75.75L16.25 17l-1.75 1.75zM3 20v-6l8-2l-8-2V4l14.3 6H17q-2.925 0-4.962 2.063T10 17.05zm10.463.538Q12 19.075 12 17t1.463-3.537T17 12t3.538 1.463T22 17t-1.463 3.538T17 22t-3.537-1.463");
}

</style>
