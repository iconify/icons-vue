<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ascu7acom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ascu7acom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:kanban-check" /></template>
