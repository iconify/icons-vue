<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf3wqoouw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:event-upcoming-outline-sharp" /></template>
<style>
.uf3wqoouw {
  fill: currentColor;
  d: path("M15.058 21v-1H19v-9.384H5V14.5H4V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16zM8 23.288l-.689-.688l3.056-3.1H1.5v-1h8.867l-3.056-3.1l.689-.688L12.289 19zM5 9.615h14V6H5zm0 0V6z");
}

</style>
