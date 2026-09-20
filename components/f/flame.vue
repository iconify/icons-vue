<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg4z99bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg4z99bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flame" /></template>
