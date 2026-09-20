<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifoqiobfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifoqiobfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:langgraph-langchain" /></template>
