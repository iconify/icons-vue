<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyunnzbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bacon-strips" /></template>
<style>
.pyunnzbao {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.397 5.364Q8 2.616 3.603 5.364q-.081.051-.147.12t-.112.152t-.07.176T3.25 6v5q0 .215.114.397q.039.063.09.117t.111.097t.127.073t.139.047t.146.019t.147-.01t.142-.039t.131-.065q3.603-2.252 7.206 0q4.397 2.748 8.794 0q.081-.051.147-.12t.112-.152t.07-.176t.024-.188V6q0-.215-.114-.397q-.079-.127-.201-.214q-.121-.086-.266-.12q-.146-.033-.293-.009q-.147.025-.273.104q-3.603 2.252-7.206 0m-8.794 8q4.397-2.748 8.794 0q3.603 2.252 7.206 0q.126-.079.273-.104t.293.009q.145.034.266.12q.122.087.201.214q.114.182.114.397v5q0 .095-.024.188q-.024.092-.07.176t-.112.152t-.147.12q-4.397 2.748-8.794 0q-3.603-2.252-7.206 0q-.126.079-.273.104t-.293-.009t-.266-.12q-.122-.087-.201-.214q-.114-.182-.114-.397v-5q0-.095.024-.188q.024-.092.07-.176t.112-.152q.066-.069.147-.12");
}

</style>
