<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vizje167c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vizje167c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layout-list-48" /></template>
