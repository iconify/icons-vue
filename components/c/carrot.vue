<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylacaac8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ylacaac8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:carrot" /></template>
