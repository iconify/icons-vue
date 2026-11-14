<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxg0ud45q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kokedama" /></template>
<style>
.jxg0ud45q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.5q-2.25 0-2.25 2.25q0 1.837 1.5 2.174v3.385Q9.171 7.348 5.907 7.756q-.176.022-.323.12q-.061.041-.114.093q-.052.052-.093.114q-.041.061-.07.129q-.028.068-.042.141t-.015.146t.014.147q.015.072.043.14t.069.13q1.326 1.99 3.428 2.792q-.456.312-.87.726Q6.25 14.118 6.25 16.5t1.684 4.066T12 22.25t4.066-1.684T17.75 16.5t-1.684-4.066q-.414-.414-.87-.726q2.102-.802 3.428-2.792q.041-.061.069-.13q.028-.068.043-.14t.014-.147q0-.074-.015-.146q-.014-.073-.042-.141t-.07-.129t-.093-.114q-.053-.052-.114-.093q-.147-.098-.323-.12q-3.264-.408-5.343 1.553V5.924q1.5-.337 1.5-2.174q0-.932-.659-1.591T12 1.5");
}

</style>
