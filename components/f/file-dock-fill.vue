<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyiib6bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyiib6bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:file-dock-fill" /></template>
