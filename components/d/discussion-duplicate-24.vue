<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l60ur6bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l60ur6bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:discussion-duplicate-24" /></template>
