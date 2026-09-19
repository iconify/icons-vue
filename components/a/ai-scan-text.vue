<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyo09cc6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyo09cc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-scan-text" /></template>
