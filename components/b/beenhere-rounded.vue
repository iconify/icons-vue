<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n561wibwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:beenhere-rounded" /></template>
<style>
.n561wibwd {
  fill: currentColor;
  d: path("M11.49 21.285q-.242-.081-.46-.243l-5.384-4.038q-.298-.218-.472-.566T5 15.713V4.616q0-.691.463-1.153T6.616 3h10.769q.69 0 1.153.463T19 4.616v11.096q0 .379-.174.727t-.472.565l-5.385 4.038q-.217.162-.46.243q-.242.08-.509.08t-.51-.08m-.54-8.404l-1.784-1.785q-.147-.146-.345-.153q-.198-.006-.363.153q-.166.166-.168.357t.162.357l1.933 1.932q.242.243.565.243t.566-.243l4.038-4.038q.146-.146.153-.344t-.153-.364q-.165-.165-.357-.168t-.356.163z");
}

</style>
