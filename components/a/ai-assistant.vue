<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-sv72byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-sv72byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ai-assistant" /></template>
