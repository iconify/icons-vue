<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws7ta51xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws7ta51xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-lock-corner-fill-round" /></template>
