<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f70cc6byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f70cc6byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-refresh-outline" /></template>
