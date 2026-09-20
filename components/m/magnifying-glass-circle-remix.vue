<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjayy9b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jjayy9b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:magnifying-glass-circle-remix" /></template>
