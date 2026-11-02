<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5w1ipogr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5w1ipogr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-root-line" /></template>
