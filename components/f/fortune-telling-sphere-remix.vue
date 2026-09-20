<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j416pfu1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j416pfu1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:fortune-telling-sphere-remix" /></template>
