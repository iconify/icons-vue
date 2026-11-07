<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2nrkubot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye-off-fill-round" /></template>
<style>
.a2nrkubot {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-4.725-4.725a10.75 10.75 0 0 1-14.491-5.597a1 1 0 0 1 0-.77a10.74 10.74 0 0 1 3.58-4.544L1.293 2.707a.999.999 0 1 1 1.414-1.414m15.722 12.893L9.53 5.287a10.75 10.75 0 0 1 12.393 6.328a1 1 0 0 1 0 .77a10.8 10.8 0 0 1-2.079 3.217Zm-5.136.522l-4.001-4.001a3.003 3.003 0 0 0 4.001 4.001");
}

</style>
