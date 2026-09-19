<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9vk905jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9vk905jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-big-up" /></template>
