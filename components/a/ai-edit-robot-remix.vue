<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izue1acve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="izue1acve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ai-edit-robot-remix" /></template>
