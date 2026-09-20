<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p50ns3biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forward-10-outline-sharp" /></template>
<style>
.p50ns3biq {
  fill: currentColor;
  d: path("M9.423 15.692v-4.5H8.039v-.884h2.269v5.384zm2.27 0v-5.384h3.769v5.384zm.884-.884h2v-3.616h-2zm-3.695 5.566q-1.455-.626-2.542-1.713t-1.714-2.543T4 13t.626-3.118T6.34 7.34t2.542-1.714T12 5h.38l-1.664-1.666l.707-.719l2.885 2.866l-2.846 2.865l-.708-.719L12.38 6H12Q9.075 6 7.038 8.038T5 13t2.038 4.963T12 20t4.963-2.037T19 13h1q0 1.664-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626");
}

</style>
