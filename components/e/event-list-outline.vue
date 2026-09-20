<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byubdtsqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:event-list-outline" /></template>
<style>
.byubdtsqw {
  fill: currentColor;
  d: path("M15.616 20q-.402 0-.701-.299t-.3-.701v-4.384q0-.402.3-.701t.7-.3H20q.402 0 .701.3t.299.7V19q0 .402-.299.701T20 20zm0-1H20v-4.384h-4.384zM3 17.308v-1h8.23v1zm12.616-6.924q-.402 0-.701-.299t-.3-.7V5q0-.402.3-.701t.7-.299H20q.402 0 .701.299T21 5v4.385q0 .401-.299.7t-.701.3zm0-1H20V5h-4.384zM3 7.692v-1h8.23v1zm14.808-.5");
}

</style>
