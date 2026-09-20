<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ninp90baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ninp90baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:goblet-fill" /></template>
