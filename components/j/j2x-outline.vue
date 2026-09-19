<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwl6l_b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hwl6l_b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:j2x-outline" /></template>
