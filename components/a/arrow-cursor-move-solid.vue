<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6b8a2bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h6b8a2bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-cursor-move-solid" /></template>
