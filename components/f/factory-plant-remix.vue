<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez1yabb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ez1yabb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:factory-plant-remix" /></template>
