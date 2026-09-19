<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4mkgjboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":541,"height":730};
const content = `<path class="y4mkgjboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:asciicircum" /></template>
