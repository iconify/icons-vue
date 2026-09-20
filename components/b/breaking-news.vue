<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmyph7bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:breaking-news" /></template>
<style>
.kmyph7bro {
  fill: currentColor;
  d: path("M7.549 16.549q.22-.22.22-.549t-.22-.549t-.549-.22t-.549.22t-.22.549t.22.549t.549.22t.549-.22M6.5 13.769h1V7.5h-1zm5 2.731h6v-1h-6zm0-4h6v-1h-6zm0-4h6v-1h-6zM4.616 20q-.691 0-1.153-.462T3 18.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v12.769q0 .69-.463 1.153T19.385 20z");
}

</style>
