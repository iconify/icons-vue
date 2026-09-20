<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw1ob8z1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw1ob8z1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-square-bold" /></template>
