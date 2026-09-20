<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozbij7j_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:delete-outline-sharp" /></template>
<style>
.ozbij7j_t {
  fill: currentColor;
  d: path("M6 20V6H5V5h4v-.77h6V5h4v1h-1v14zm1-1h10V6H7zm2.808-2h1V8h-1zm3.384 0h1V8h-1zM7 6v13z");
}

</style>
