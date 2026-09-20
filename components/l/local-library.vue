<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvyjzsycm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-library" /></template>
<style>
.qvyjzsycm {
  fill: currentColor;
  d: path("M12 21.116q-1.684-1.374-3.721-2.168T4 18V8.654q2.294.135 4.36 1.095q2.065.96 3.64 2.378q1.575-1.418 3.64-2.378T20 8.654V18q-2.248.154-4.282.948T12 21.116M9.714 7.633q-.945-.944-.945-2.287t.944-2.286T12 2.116t2.286.944t.945 2.286t-.944 2.287T12 8.577t-2.286-.944");
}

</style>
