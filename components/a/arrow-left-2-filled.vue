<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl69xg8ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl69xg8ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left-2-filled" /></template>
