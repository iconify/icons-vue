<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acayooksy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acayooksy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:kanban-solid" /></template>
