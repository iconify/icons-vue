<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs6eumz8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xs6eumz8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:iron-three" /></template>
