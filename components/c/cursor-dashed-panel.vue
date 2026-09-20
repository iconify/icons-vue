<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfbuyzb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfbuyzb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-dashed-panel" /></template>
