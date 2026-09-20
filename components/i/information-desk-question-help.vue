<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odx7qtvdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odx7qtvdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:information-desk-question-help" /></template>
