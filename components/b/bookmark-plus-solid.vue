<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-pzc6fpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-pzc6fpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bookmark-plus-solid" /></template>
