<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr41qglch.css';
import '../../css/y/yph1tgb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr41qglch"/><path class="yph1tgb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-left-stroke-circle-half" /></template>
