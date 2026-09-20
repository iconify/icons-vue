<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9g99qbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-4-rounded" /></template>
<style>
.x9g99qbha {
  fill: currentColor;
  d: path("M13.5 12.5V16q0 .214.143.357T14 16.5t.357-.143T14.5 16V8q0-.213-.143-.357T14 7.5t-.357.143T13.5 8v3.5h-3V8q0-.213-.143-.357T10 7.5t-.357.143T9.5 8v3.692q0 .348.23.578t.578.23zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
