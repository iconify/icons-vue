<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxslm2bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forward-30-outline-sharp" /></template>
<style>
.gxslm2bqf {
  fill: currentColor;
  d: path("M7.539 15.692v-.884h2.884v-1.423H8.346v-.77h2.077v-1.423H7.539v-.884h3.769v5.384zm5.153 0v-5.384h3.77v5.384zm.885-.884h2v-3.616h-2zm-4.695 5.566q-1.455-.626-2.542-1.713t-1.714-2.543T4 13t.626-3.118T6.34 7.34t2.542-1.714T12 5h.38l-1.664-1.666l.707-.719l2.885 2.866l-2.846 2.865l-.708-.719L12.38 6H12Q9.075 6 7.038 8.038T5 13t2.038 4.963T12 20t4.963-2.037T19 13h1q0 1.664-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626");
}

</style>
