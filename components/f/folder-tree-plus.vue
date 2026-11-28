<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gff683b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gff683b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-tree-plus" /></template>
