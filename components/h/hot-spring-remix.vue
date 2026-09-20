<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srgcg9p3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srgcg9p3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hot-spring-remix" /></template>
