<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caigzjn8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-awesome-motion" /></template>
<style>
.caigzjn8n {
  fill: currentColor;
  d: path("M12.616 21q-.691 0-1.153-.462T11 19.385v-6.77q0-.69.463-1.152T12.616 11h6.769q.69 0 1.153.463T21 12.616v6.769q0 .69-.462 1.153T19.385 21zM7 17.23V8.617q0-.691.463-1.153T8.616 7h8.615v1H8.616q-.231 0-.424.192T8 8.616v8.615zm-4-4V4.617q0-.691.463-1.153T4.615 3h8.616v1H4.616q-.231 0-.424.192T4 4.615v8.616z");
}

</style>
