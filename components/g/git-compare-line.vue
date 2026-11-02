<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiu379ggu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiu379ggu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-compare-line" /></template>
