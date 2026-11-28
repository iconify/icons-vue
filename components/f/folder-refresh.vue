<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfqz4bcsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfqz4bcsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-refresh" /></template>
