<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb6uyu7ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fax-outline-sharp" /></template>
<style>
.mb6uyu7ii {
  fill: currentColor;
  d: path("M2 21V8h6v1v-5h10v5h4v11H8v1zm2-2h2v-9H4zm6-10h6V6h-6zm-2 9h12v-7H8zm1-1h4v-5H9zm-1 1v-7zm6-4h2v-2h-2zm3 0h2v-2h-2zm-3 3h2v-2h-2zm3 0h2v-2h-2z");
}

</style>
