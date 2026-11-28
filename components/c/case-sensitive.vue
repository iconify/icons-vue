<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggor3gbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggor3gbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:case-sensitive" /></template>
