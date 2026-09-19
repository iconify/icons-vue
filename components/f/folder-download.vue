<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_glu1b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_glu1b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:folder-download" /></template>
