<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp4-eacar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keep-public-outline" /></template>
<style>
.qp4-eacar {
  fill: currentColor;
  d: path("m9 20.5l-.5-.5v-5H4.423v-1L6 12.423V5H5V4h6.048q-.2.233-.37.473t-.31.527H7v7.85L5.85 14h7.133q.138.08.285.136q.147.055.309.078V15H9.5v5zm8.063-12.937q.437-.438.437-1.063t-.437-1.062T16 5t-1.062.438T14.5 6.5t.438 1.063T16 8t1.063-.437m.34 3.084q.647-.353 1.072-.978q-.57-.338-1.194-.504Q16.656 9 16 9t-1.28.166q-.626.165-1.195.503q.425.625 1.072.978T16 11t1.403-.353m-4.238.189Q12 9.67 12 8t1.165-2.835T16 4t2.836 1.165T20 8t-1.164 2.836T16 12t-2.835-1.164");
}

</style>
