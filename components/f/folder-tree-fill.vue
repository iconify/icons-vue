<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlbudvxom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlbudvxom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-tree-fill" /></template>
