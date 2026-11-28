<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdwzq7clc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdwzq7clc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-open-plus" /></template>
