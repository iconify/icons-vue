<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkzg49b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkzg49b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bot-off" /></template>
