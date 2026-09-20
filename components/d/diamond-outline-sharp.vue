<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8c050b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:diamond-outline-sharp" /></template>
<style>
.m8c050b6i {
  fill: currentColor;
  d: path("M12 20.212L2.596 8.923L5.308 3.5h13.384l2.712 5.423zM8.817 8.5h6.366l-2-4h-2.366zm2.683 9.56V9.5H4.392zm1 0l7.108-8.56H12.5zm3.792-9.56h3.766l-2-4h-3.766zm-12.35 0h3.766l2-4H5.942z");
}

</style>
