<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya7zfsbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ya7zfsbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-strikethrough" /></template>
