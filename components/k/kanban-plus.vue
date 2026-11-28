<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcvw__bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcvw__bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:kanban-plus" /></template>
