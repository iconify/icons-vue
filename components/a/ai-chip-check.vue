<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4ic54bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4ic54bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ai-chip-check" /></template>
