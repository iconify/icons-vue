<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-dnt8gvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-dnt8gvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:claude-code" /></template>
