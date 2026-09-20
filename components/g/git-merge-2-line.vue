<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8ufys8yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8ufys8yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-merge-2-line" /></template>
