<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/preos7pch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="preos7pch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-play" /></template>
