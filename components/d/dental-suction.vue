<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0xn595kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-suction" /></template>
<style>
.p0xn595kt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m17.312 2.416l-4 1.285q-1.259.405-1.503 1.549H9q-2.175 0-3.712 1.538Q3.75 8.325 3.75 10.5v11q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-11q0-1.553 1.098-2.652Q7.447 6.75 9 6.75h2.809q.244 1.144 1.503 1.549l4 1.285q1.089.35 2.013-.324q.925-.674.925-1.818V4.558q0-1.144-.925-1.818q-.924-.674-2.013-.324m-.936 9.668q.083-.125.208-.208q.061-.041.13-.069q.068-.028.14-.043t.147-.014t.146.015q.073.014.141.042t.129.07t.114.093q.052.053.093.114q.259.388.766 1.081q1.36 1.858 1.36 2.835q0 2.75-2.75 2.75T14.25 16q0-.977 1.36-2.835q.507-.693.766-1.081");
}

</style>
