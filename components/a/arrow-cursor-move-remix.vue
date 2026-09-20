<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-e1kac9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d-e1kac9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-cursor-move-remix" /></template>
