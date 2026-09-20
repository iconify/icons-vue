<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy_pu7xll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dy_pu7xll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:filter-1-remix" /></template>
