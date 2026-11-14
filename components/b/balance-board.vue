<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmwa2yq9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balance-board" /></template>
<style>
.mmwa2yq9t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.083 6.712L3.734 8.87h-.001q-2.474.349-2.127 2.823q.347 2.476 2.823 2.129l4.987-.701q-.217.17-.421.374Q7.75 14.74 7.75 16.5t1.245 3.005T12 20.75t3.005-1.245T16.25 16.5t-1.245-3.005q-.647-.648-1.434-.958l6.209-.873q2.474-.349 2.127-2.823q-.144-1.026-.971-1.65q-.828-.623-1.853-.479");
}

</style>
