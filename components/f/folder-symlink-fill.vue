<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3upq6s7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3upq6s7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-symlink-fill" /></template>
