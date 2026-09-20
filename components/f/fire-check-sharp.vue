<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-9ysebsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fire-check-sharp" /></template>
<style>
.d-9ysebsu {
  fill: currentColor;
  d: path("m16.235 19.598l4.057-4.057l.708.713L16.24 21l-2.742-2.723l.708-.708zM5 13q0-2.571 1.615-5.029T11 3.79V5.3q0 1.273.876 2.137t2.149.863q.47 0 .915-.159q.445-.158.84-.456l.432-.339q1.396 1.064 2.141 2.697t.609 3.446l-2.727 2.746l-2.03-2.03l-4.09 4.072l1.718 1.717q-.03 0-.061.003t-.06.003Q8.9 19.885 6.95 17.867T5 13");
}

</style>
