<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewyi4hbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:breaking-news-alt-1" /></template>
<style>
.ewyi4hbne {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v12.769q0 .69-.463 1.153T19.385 20zm2.153-3.5h4.462v-1H6.769zm0-4h4.462v-1H6.769zm0-4h4.462v-1H6.769zm9.462 8h1v-1h-1zm0-4h1v-5h-1z");
}

</style>
