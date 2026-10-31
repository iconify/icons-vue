<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc33240jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc33240jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-horizontal-fill-round" /></template>
