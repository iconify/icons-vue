<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2luwybss.css';
import '../../css/e/ekdghkqub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2luwybss"/><path class="ekdghkqub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:design-tool-pen-brush-cup" /></template>
