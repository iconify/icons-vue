<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5fghab-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5fghab-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-close-fill-round" /></template>
