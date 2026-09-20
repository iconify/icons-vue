<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgffrtbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:image-aspect-ratio" /></template>
<style>
.bgffrtbax {
  fill: currentColor;
  d: path("M6.192 12h1.616v-1.616H6.192zM10 12h1.616v-1.616H10zm3.808 3.808h1.615v-1.616h-1.615zm0-3.808h1.615v-1.616h-1.615zm-9.192 7q-.691 0-1.154-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
