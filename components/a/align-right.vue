<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk-ngov9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk-ngov9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:align-right" /></template>
