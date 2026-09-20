<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b79l61bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b79l61bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:langgraph-langchain" /></template>
