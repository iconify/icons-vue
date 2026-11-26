<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezu2wp9xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-d8-fill" /></template>
<style>
.ezu2wp9xb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 12L22 15.4917C22 16.9129 21.2459 18.2274 20.0191 18.9448L14.0191 22.4531C13.4064 22.8112 12.7096 23 12 23C11.2904 23 10.5936 22.8112 9.981 22.4531L3.9809 18.9448C2.7541 18.2274 2 16.9129 2 15.4917L2 8.5083C2 7.0871 2.7541 5.7726 3.9809 5.0552L9.9809 1.5469C10.5936 1.1888 11.2904 1 12 1C12.7096 1 13.4064 1.1888 14.019 1.5469L20.0191 5.0552C21.2459 5.7726 22 7.0871 22 8.5083ZM8.5662 9.9902L5.1249 15.9846L18.8751 15.9846L12 4.0086Z");
}

</style>
