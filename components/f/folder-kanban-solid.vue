<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfhzjy5gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfhzjy5gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder-kanban-solid" /></template>
