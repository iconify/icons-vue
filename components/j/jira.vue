<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4yqyt6tg.css';
import '../../css/n/nnl6f83rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="e4yqyt6tg"/><path class="nnl6f83rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:jira" /></template>
