<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on9qdlkrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on9qdlkrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layout-dashboard-sharp-fill" /></template>
