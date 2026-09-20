<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra000ibse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:analytics" /></template>
<style>
.ra000ibse {
  fill: currentColor;
  d: path("M7.73 16.5h1V12h-1zm7.54 0h1V7h-1zm-3.77 0h1V14h-1zm0-4.5h1v-2h-1zm-5.884 8q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
