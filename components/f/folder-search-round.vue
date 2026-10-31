<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud6q_xb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud6q_xb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-search-round" /></template>
