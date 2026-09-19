<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf4l44b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf4l44b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-text" /></template>
