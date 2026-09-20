<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzkndbbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:4g-mobiledata-badge-sharp" /></template>
<style>
.pzkndbbuw {
  fill: currentColor;
  d: path("M12.923 16.5h6v-5h-2.115v1h1.115v3h-4v-7h5v-1h-6zm-4.423 0h1v-3h2v-1h-2v-5h-1v5h-3v-5h-1v6h4zM2 20V4h20v16z");
}

</style>
