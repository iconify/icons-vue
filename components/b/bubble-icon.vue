<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":276};
const content = `<path class="qo4z8yd9i"/><path class="l36nyxb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:bubble-icon" /></template>
<style>
.l36nyxb5d {
  fill: var(--svg-color--00f, #00f);
  d: path("M25.22 225.066c-13.93 0-25.22 11.292-25.22 25.22s11.291 25.22 25.22 25.22s25.22-11.292 25.22-25.22s-11.291-25.22-25.22-25.22");
}

.qo4z8yd9i {
  fill: var(--svg-color--262626, #262626);
  d: path("M156.688 71.53c-24.76 0-49.164 10.63-67.795 31.529V0H52.024v173.519c0 56.326 45.661 101.988 101.988 101.988S256 229.845 256 173.519S213.014 71.531 156.688 71.531m-2.676 164.694c-34.632 0-62.707-28.075-62.707-62.706s28.075-62.707 62.707-62.707c34.631 0 62.706 28.075 62.706 62.707s-28.075 62.706-62.706 62.706");
}

</style>
