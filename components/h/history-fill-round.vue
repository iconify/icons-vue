<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5xmfj1jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5xmfj1jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:history-fill-round" /></template>
