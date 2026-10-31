<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi92mggmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi92mggmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-pull-request-fill-round" /></template>
