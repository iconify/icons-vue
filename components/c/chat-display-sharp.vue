<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d47mx6m5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-display-sharp" /></template>
<style>
.d47mx6m5h {
  fill: currentColor;
  d: path("M12.327 21v-6.115H21V21zm1-1H20v-4.115h-6.673zM6.5 10.5h11v-1h-11zm0-3h11v-1h-11zM9.942 17H6.077L3 20.077V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616V12.5H6.5v1h3.442z");
}

</style>
