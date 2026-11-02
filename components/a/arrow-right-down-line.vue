<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvsh8gd7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvsh8gd7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-down-line" /></template>
