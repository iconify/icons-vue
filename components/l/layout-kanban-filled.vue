<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqiaqzg6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqiaqzg6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-kanban-filled" /></template>
