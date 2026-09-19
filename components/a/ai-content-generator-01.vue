<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye8y2k9kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye8y2k9kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-content-generator-01" /></template>
