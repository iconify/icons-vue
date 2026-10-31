<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aemvm93ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aemvm93ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-tree-duotone-round" /></template>
