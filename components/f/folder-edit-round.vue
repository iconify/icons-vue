<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzuv5c50q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzuv5c50q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-edit-round" /></template>
