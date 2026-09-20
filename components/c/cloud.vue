<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8x1f8b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8x1f8b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cloud" /></template>
