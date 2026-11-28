<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onfod63xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onfod63xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:kanban-solid" /></template>
