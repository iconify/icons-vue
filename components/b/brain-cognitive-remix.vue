<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz3w198jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cz3w198jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:brain-cognitive-remix" /></template>
