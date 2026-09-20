<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd7yvvb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd7yvvb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:inoreader" /></template>
