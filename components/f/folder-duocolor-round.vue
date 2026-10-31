<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3i9qpgha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3i9qpgha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-duocolor-round" /></template>
