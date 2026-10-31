<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iirmefbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iirmefbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-search-corner-fill-round" /></template>
