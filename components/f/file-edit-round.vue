<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i24o6qbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i24o6qbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-edit-round" /></template>
