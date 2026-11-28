<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3up-8bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3up-8bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:line-chart" /></template>
