<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j82880bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j82880bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:linux" /></template>
