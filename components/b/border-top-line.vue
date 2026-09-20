<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn82-tbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn82-tbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-top-line" /></template>
