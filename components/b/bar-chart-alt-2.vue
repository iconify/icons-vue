<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rew8143lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rew8143lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bar-chart-alt-2" /></template>
