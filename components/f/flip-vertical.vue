<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb4c10b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="jb4c10b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:flip-vertical" /></template>
