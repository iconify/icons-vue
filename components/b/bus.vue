<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czum-8bsq.css';
import '../../css/v/vk88lsh0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czum-8bsq duoicon-secondary-layer"/><path class="duoicon-primary-layer vk88lsh0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:bus" /></template>
