<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wczeb9phz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wczeb9phz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:folder-kanban" /></template>
