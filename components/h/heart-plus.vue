<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_gzc8c8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_gzc8c8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:heart-plus" /></template>
