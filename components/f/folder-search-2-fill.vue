<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/untafkwvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="untafkwvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-search-2-fill" /></template>
