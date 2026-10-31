<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1kwpebff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1kwpebff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-edit-corner-fill-round" /></template>
