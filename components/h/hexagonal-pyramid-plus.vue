<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk5app3bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk5app3bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagonal-pyramid-plus" /></template>
