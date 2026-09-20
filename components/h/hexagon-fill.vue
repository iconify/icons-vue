<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-4jvccaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-4jvccaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hexagon-fill" /></template>
