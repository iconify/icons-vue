<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/powdozs3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="powdozs3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:human-resources-hierarchy-1-bold" /></template>
