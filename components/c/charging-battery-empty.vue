<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocgok7zrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocgok7zrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:charging-battery-empty" /></template>
