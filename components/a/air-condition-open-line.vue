<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdsr3dryb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdsr3dryb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:air-condition-open-line" /></template>
