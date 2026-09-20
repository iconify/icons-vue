<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrxrdd0dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-check-2" /></template>
<style>
.xrxrdd0dl {
  fill: currentColor;
  d: path("M20.143 14.857q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165M10.943 18l.036.506q.017.25.09.494H4.615q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.981l2 2h7.789q.69 0 1.153.463T21 8.616v3.87q-.817-.586-1.756-.882q-.938-.296-1.936-.296q-2.766 0-4.633 1.973T10.942 18m5.66 1.712l3.34-3.335l-.626-.627l-2.714 2.702L15.3 17.15l-.627.633z");
}

</style>
