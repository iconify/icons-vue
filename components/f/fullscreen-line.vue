<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5hgvirvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5hgvirvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fullscreen-line" /></template>
