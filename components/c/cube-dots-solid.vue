<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl-44q3kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jl-44q3kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cube-dots-solid" /></template>
