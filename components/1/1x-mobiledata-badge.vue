<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb8w7j_ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:1x-mobiledata-badge" /></template>
<style>
.zb8w7j_ak {
  fill: currentColor;
  d: path("M3.616 20q-.691 0-1.153-.462T2 18.384V5.616q0-.691.463-1.153T3.616 4h16.769q.69 0 1.153.463T22 5.616v12.769q0 .69-.462 1.153T20.385 20zM7.5 16.5h1v-9h-3v1h2zm4.462 0h1.077l2.211-3.752l2.212 3.752h1.115l-2.77-4.73l2.5-4.27h-1.076l-1.962 3.348L13.308 7.5h-1.116l2.52 4.308z");
}

</style>
