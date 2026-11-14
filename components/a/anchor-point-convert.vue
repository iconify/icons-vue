<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqv02byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anchor-point-convert" /></template>
<style>
.yzqv02byq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 16.087q1.872-.771 4.637-5.197q4.102-6.565 7.49-7.13q.147-.024.292.009q.146.034.267.121q.121.086.2.213t.104.274q.012.073.01.146q-.003.074-.019.146q-.017.072-.047.139q-.031.068-.074.128t-.096.111q-.054.05-.117.089t-.132.066t-.142.038q-2.72.453-6.464 6.445q-3.303 5.289-5.909 5.966V18q0 2.25-2.25 2.25h-2q-2.25 0-2.25-2.25v-2q0-.932.659-1.591T4.5 13.75h.25v-3.56q-2-.345-2-2.69q0-2.75 2.75-2.75T8.25 7.5q0 2.345-2 2.69v3.56h.25q2.25 0 2.25 2.25z");
}

</style>
