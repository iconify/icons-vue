<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm5qhb-sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:elevator-outline" /></template>
<style>
.rm5qhb-sn {
  fill: currentColor;
  d: path("M7.885 17.5h2v-3.808h1v-2.576q0-.633-.434-1.067t-1.066-.433h-1q-.633 0-1.067.433q-.433.434-.433 1.067v2.576h1zm1.753-9.112q.304-.305.304-.754q0-.448-.305-.752t-.753-.305t-.752.305t-.305.752q0 .449.305.753t.752.305t.753-.305m4.075 2.113h3.192l-1.596-2.558zm1.596 5.558l1.596-2.558h-3.192zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm0-1h12.769q.269 0 .442-.173t.173-.442V5.615q0-.269-.173-.442T18.385 5H5.615q-.269 0-.442.173T5 5.616v12.769q0 .269.173.442t.443.173M5 19V5z");
}

</style>
