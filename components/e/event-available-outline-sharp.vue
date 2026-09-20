<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmicgtb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:event-available-outline-sharp" /></template>
<style>
.nmicgtb-a {
  fill: currentColor;
  d: path("m10.95 17.62l-2.858-2.858l.72-.72l2.138 2.139l4.239-4.239l.719.72zM4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16zm1-1h14v-9.384H5zM5 9.615h14V6H5zm0 0V6z");
}

</style>
