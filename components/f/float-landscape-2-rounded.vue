<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evwnfu4qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:float-landscape-2-rounded" /></template>
<style>
.evwnfu4qy {
  fill: currentColor;
  d: path("M13.423 14.385h3.385q.348 0 .577-.23q.23-.23.23-.578V9.192q0-.348-.23-.578t-.577-.23h-3.385q-.348 0-.578.23t-.23.578v4.385q0 .348.23.578t.578.23M4.615 19q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
