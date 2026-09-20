<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa2wmjajw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa2wmjajw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:color-filter-ai-fill" /></template>
