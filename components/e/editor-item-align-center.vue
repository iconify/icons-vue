<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfybttfyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rfybttfyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-item-align-center" /></template>
