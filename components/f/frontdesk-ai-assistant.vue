<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol-y4ub0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol-y4ub0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:frontdesk-ai-assistant" /></template>
