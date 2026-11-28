<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi6h-tbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi6h-tbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layout-masonry-solid" /></template>
