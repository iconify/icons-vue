<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl6l9g10r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl6l9g10r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:diamond-minus" /></template>
