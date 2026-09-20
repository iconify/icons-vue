<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd3oymqif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cleaning-outline-sharp" /></template>
<style>
.zd3oymqif {
  fill: currentColor;
  d: path("M9.866 8.116L10.98 6v-.77H9.596V4h5.616v1.462l-.885 1.769h-1.923V6.192l-1.846 1.924zM8.789 21v-6.194L12.404 8h2.385v13zm1-1h4V9h-.781l-3.22 6.08zm0 0h4z");
}

</style>
