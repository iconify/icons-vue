<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl1jl-bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl1jl-bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:baseline" /></template>
