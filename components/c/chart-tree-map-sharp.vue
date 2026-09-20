<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc7cseb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc7cseb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-tree-map-sharp" /></template>
