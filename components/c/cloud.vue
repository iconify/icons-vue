<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erx1m70kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erx1m70kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cloud" /></template>
