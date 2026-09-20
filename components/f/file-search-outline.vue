<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jee5rlb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jee5rlb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-search-outline" /></template>
