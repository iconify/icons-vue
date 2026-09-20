<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrtyf4o6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hangout-video-outline" /></template>
<style>
.yrtyf4o6a {
  fill: currentColor;
  d: path("M6.923 15.385h6.77v-2.7l3.384 2.7v-6.77l-3.385 2.7v-2.7H6.923zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.269 0 .442-.173t.173-.442V6.615q0-.269-.173-.442T19.385 6H4.615q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173M4 6v12z");
}

</style>
