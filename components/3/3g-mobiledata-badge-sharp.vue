<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1udjtbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:3g-mobiledata-badge-sharp" /></template>
<style>
.b1udjtbeu {
  fill: currentColor;
  d: path("M12 17h7v-6h-3v2h1v2h-3V9h5V7h-7zm-7 0h6v-4l-1-1l1-1V7H5v2h4v2H5v2h4v2H5zm-4 4V3h22v18z");
}

</style>
