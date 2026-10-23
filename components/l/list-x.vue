<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlgm-dd3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlgm-dd3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-x" /></template>
