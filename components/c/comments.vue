<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdokiyzji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qdokiyzji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:comments" /></template>
