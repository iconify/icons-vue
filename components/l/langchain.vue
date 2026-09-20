<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzisgdc9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzisgdc9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:langchain" /></template>
