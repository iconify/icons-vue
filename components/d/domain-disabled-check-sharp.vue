<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfnc88q5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:domain-disabled-check-sharp" /></template>
<style>
.zfnc88q5k {
  fill: currentColor;
  d: path("M20.5 23.3L18.15 21H2V4.8L.7 3.5l1.4-1.4l19.8 19.8zM4 19h2v-2H4zm0-4h2v-2H4zm0-4h2V9H4zm4 8h2v-2H8zm0-4h2v-2H8zm4 4h4.15l-2-2H12zm5.275-10.75l3.55-3.55l-.7-.7L17.3 6.825L15.875 5.4l-.7.725zm4.263-5.787Q23 3.925 23 6t-1.463 3.538T18 11t-3.537-1.463T13 6t1.463-3.537T18 1t3.538 1.463M22 19.15l-2-2V13h2zm-10-10l-2-2V5H7.85l-2-2H12z");
}

</style>
