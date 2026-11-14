<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0p-xlxzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:event-correlation" /></template>
<style>
.u0p-xlxzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.25q-3.25 0-3.25 3.25q0 2.85 2.5 3.201v1.338Q8 9.394 8 13q0 1.153.332 1.974l-1.117.893Q6.416 15.25 5 15.25q-3.25 0-3.25 3.25T5 21.75t3.25-3.25q0-.789-.192-1.386l1.154-.923Q10.201 17 12 17t2.788-.809l1.154.923q-.192.597-.192 1.386q0 3.25 3.25 3.25t3.25-3.25T19 15.25q-1.416 0-2.215.617l-1.117-.893Q16 14.153 16 13q0-1.657-1.172-2.828q-.897-.897-2.078-1.108V7.701q2.5-.351 2.5-3.201q0-3.25-3.25-3.25");
}

</style>
