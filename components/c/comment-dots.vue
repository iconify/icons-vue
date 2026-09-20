<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krnc8kyjp.css';
import '../../css/f/f0fcqmbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krnc8kyjp"/><path class="f0fcqmbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:comment-dots" /></template>
