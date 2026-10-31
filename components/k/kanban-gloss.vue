<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhqw6obtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhqw6obtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:kanban-gloss" /></template>
