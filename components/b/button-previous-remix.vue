<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn7vb6x8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mn7vb6x8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-previous-remix" /></template>
