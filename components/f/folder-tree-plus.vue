<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grwkuj16h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grwkuj16h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-tree-plus" /></template>
