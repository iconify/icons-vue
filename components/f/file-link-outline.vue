<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-3wim6xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-3wim6xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-link-outline" /></template>
