<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jewsv4wxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jewsv4wxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:love-fill" /></template>
