<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp4eihbdx.css';
import '../../css/v/vox3mdpjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hp4eihbdx"/><path class="vox3mdpjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brain-off-filled" /></template>
