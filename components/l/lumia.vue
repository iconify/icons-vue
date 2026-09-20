<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7i0c4bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lumia" /></template>
<style>
.y7i0c4bhh {
  d: path("M8.647 11.686H3l5.941-2.76L11.691 3l.006 5.63a3.054 3.054 0 0 1-3.052 3.058zm6.706 0H21l-5.941-2.76L12.309 3l-.006 5.63a3.054 3.054 0 0 0 3.052 3.058zm0 .628H21l-5.941 2.76L12.309 21l-.006-5.63a3.054 3.054 0 0 1 3.052-3.058zm-6.706 0H3l5.941 2.76L11.691 21l.006-5.63a3.054 3.054 0 0 0-3.052-3.058z");
}

</style>
