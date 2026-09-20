<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyejujtbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:high-quality-outline-sharp" /></template>
<style>
.oyejujtbd {
  fill: currentColor;
  d: path("M14.75 16.192h.885v-1.5h1.75V9.308H13v5.384h1.75zm-8.135-1.5H7.5v-2h2.616v2H11V9.308h-.885v2.5H7.5v-2.5h-.885zm7.27-.884v-3.616H16.5v3.616zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
