<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqw_-fb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forest-outline-sharp" /></template>
<style>
.lqw_-fb-w {
  fill: currentColor;
  d: path("M8 21v-4H1.885l3.965-6H3.923L9 3.73l3 4.3l3-4.3L20.077 11H18.15l3.966 6H16v4h-2v-4h-4v4zm7.456-5h4.817l-3.971-6h1.848L15 5.5l-2.371 3.39L14.077 11H12.15zM3.727 16h10.546l-3.971-6h1.848L9 5.5L5.85 10h1.848zm0 0h3.971H5.85h6.3h-1.848h3.971zm11.729 0H12.15h1.927h-1.448h5.521h-1.848h3.971zM14 17h2zm2.121 0");
}

</style>
