<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi8vsubkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="yi8vsubkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:fullscreen-exit" /></template>
