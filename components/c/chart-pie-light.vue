<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctceaps1p.css';
import '../../css/y/yg4acmb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctceaps1p"/><path class="yg4acmb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chart-pie-light" /></template>
