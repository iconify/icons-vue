<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff5cec_vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-clear-sharp" /></template>
<style>
.ff5cec_vx {
  fill: currentColor;
  d: path("m12.546 9.966l-.94-.941l.788-1.904h-2.73L8.427 5.885h10.689v1.23h-5.358zm6.793 10.788l-7.973-7.993l-2.308 5.431H7.706l2.725-6.365l-7.377-7.358l.708-.707l16.284 16.284z");
}

</style>
