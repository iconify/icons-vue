<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv0vsshty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:garage-door-rounded" /></template>
<style>
.wv0vsshty {
  fill: currentColor;
  d: path("M6 20q-.825 0-1.412-.587T4 18v-8H2.525q-.35 0-.475-.35t.175-.55l8.6-6.25q.525-.375 1.175-.375t1.175.375L21.75 9.1q.3.2.175.55t-.475.35H20v8q0 .825-.587 1.413T18 20zm2-1.5h8V17H8zm0-3h8V14H8zm0-3h8V11H8zM12 8q.425 0 .713-.288T13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8");
}

</style>
