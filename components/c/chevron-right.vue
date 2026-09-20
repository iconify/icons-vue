<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gay3w-bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gay3w-bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chevron-right" /></template>
