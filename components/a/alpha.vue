<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hutwm4b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hutwm4b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:alpha" /></template>
