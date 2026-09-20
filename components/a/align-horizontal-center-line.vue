<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u25n3tb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u25n3tb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-center-line" /></template>
