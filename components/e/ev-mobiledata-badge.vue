<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km5rm0mcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ev-mobiledata-badge" /></template>
<style>
.km5rm0mcg {
  fill: currentColor;
  d: path("M3.616 20q-.691 0-1.153-.462T2 18.384V5.616q0-.691.463-1.153T3.616 4h16.769q.69 0 1.153.463T22 5.616v12.769q0 .69-.462 1.153T20.385 20zm2.269-3.5h4.884v-1H6.885v-3h2.884v-1H6.885v-3h3.884v-1H5.885zm9 0h1.077l2.692-9h-1.038l-2.193 7.23l-2.192-7.23h-1.039z");
}

</style>
