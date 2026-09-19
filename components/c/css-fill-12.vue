<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6qe8n8xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f6qe8n8xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:css-fill-12" /></template>
