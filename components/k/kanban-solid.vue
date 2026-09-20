<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz_intbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz_intbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:kanban-solid" /></template>
