<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxuuh2bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sxuuh2bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:key" /></template>
