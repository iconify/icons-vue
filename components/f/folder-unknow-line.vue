<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prht9cg7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prht9cg7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-unknow-line" /></template>
