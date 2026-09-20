<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeteyhbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-open-outline-sharp" /></template>
<style>
.eeteyhbqe {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2h9.231v1h-9.633l-2-2H4v11.962l2.266-7.577h16.6L20.288 19zm2.042-1H19.54l1.973-6.616H7.015zm0 0l1.974-6.616zM4 8V6z");
}

</style>
