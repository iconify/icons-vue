<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz8l0fcbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:developer-guide-rounded" /></template>
<style>
.bz8l0fcbi {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zM12.5 5v5.414q0 .242.202.36t.414-.012l.975-.597q.192-.13.409-.13t.41.13l.974.597q.212.13.414.012t.202-.36V5z");
}

</style>
