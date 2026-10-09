<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy7xqk_um.css';
import '../../css/h/hs5ndsbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xy7xqk_um"/><path class="hs5ndsbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kanban-48-bold" /></template>
