<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsskbnj7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qsskbnj7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-1-fill" /></template>
