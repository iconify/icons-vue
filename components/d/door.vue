<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il4iknbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="il4iknbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:door" /></template>
