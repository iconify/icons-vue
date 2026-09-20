<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1c916b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1c916b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:diagram-arrow-down-1-bold" /></template>
