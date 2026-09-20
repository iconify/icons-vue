<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6pyo-bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clinical-notes-sharp" /></template>
<style>
.y6pyo-bkg {
  fill: currentColor;
  d: path("M15.366 14.962q-.674-.673-.674-1.635t.674-1.635T17 11.02t1.635.673q.673.674.673 1.635t-.674 1.635t-1.634.673t-1.634-.673m-3.674 6.576v-3.101q.858-.504 1.775-.837t1.887-.494L17 19.25l1.627-2.144q.989.13 1.906.488t1.775.837v3.107zM8.923 20H4V4h16v5.308q-.64-.514-1.394-.786T17 8.25q-.134 0-.25.01t-.25.028v-.557h-9v1h7.423q-.923.4-1.602 1.111q-.679.712-1.05 1.658H7.5v1h4.52q-.097.621-.052 1.246t.245 1.235q-.172.077-.336.144t-.318.144H7.5v1h1.423z");
}

</style>
