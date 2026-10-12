<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy7ws3bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gy7ws3bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:code-bracket-20" /></template>
