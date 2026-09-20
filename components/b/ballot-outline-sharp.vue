<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iznm5k9vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ballot-outline-sharp" /></template>
<style>
.iznm5k9vc {
  fill: currentColor;
  d: path("M12 10h4.616V9H12zm0 5h4.616v-1H12zm-4.23-4.27h2.46V8.27H7.77zm0 5h2.46v-2.46H7.77zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
