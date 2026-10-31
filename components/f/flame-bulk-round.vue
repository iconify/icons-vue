<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtgqigzcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtgqigzcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flame-bulk-round" /></template>
