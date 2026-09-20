<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4ac3gbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q4ac3gbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:charging-remix" /></template>
