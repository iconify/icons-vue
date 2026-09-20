<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no-uftbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-check" /></template>
<style>
.no-uftbco {
  fill: currentColor;
  d: path("M5.616 21q-.691 0-1.153-.462T4 19.385V6.615q0-.69.463-1.152T5.616 5h1.769V2.77h1.077V5h7.154V2.77h1V5h1.769q.69 0 1.153.463T20 6.616v6.586l-1 1v-3.586H5v8.769q0 .23.192.423t.423.192h5.95l1.02 1zm10.857.5l-2.742-2.723l.708-.708l2.028 2.029l4.058-4.057l.708.713z");
}

</style>
