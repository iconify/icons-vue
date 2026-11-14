<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2f_69b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:check-square" /></template>
<style>
.z2f_69b1b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.375 2.75h-4.75q-2.848 0-4.861 2.014T2.75 9.625v4.75q0 2.848 2.014 4.861t4.861 2.014h4.75q2.848 0 4.861-2.014t2.014-4.861v-4.75q0-2.848-2.014-4.861T14.375 2.75M10.95 14.389l4.474-5.369q.047-.057.105-.103q.057-.047.122-.081q.066-.034.137-.055t.144-.028t.147.001t.144.03q.071.022.136.057q.064.036.121.083t.103.105t.081.122q.034.066.055.137t.028.144t-.001.147t-.03.144t-.057.136q-.036.064-.083.121l-5 6q-.022.026-.046.05q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-3-3q-.106-.105-.163-.243T7.25 12.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8 11.75t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
