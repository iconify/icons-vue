<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw-ntzb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-asterisk" /></template>
<style>
.xw-ntzb6f {
  fill: currentColor;
  d: path("m17.683 21.777l-.866-.5L18.14 19H15.5v-1h2.64l-1.323-2.277l.866-.5L19 17.5l1.317-2.277l.866.5L19.86 18h2.64v1h-2.64l1.323 2.277l-.866.5L19 19.5zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v6.351q-.477-.183-.97-.28T19 12.592q-2.461 0-4.185 1.724T13.09 18.5q0 .14.012.253t.024.247zM12 12.116l8-5.212L19.692 6L12 11L4.308 6L4 6.904z");
}

</style>
