<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjg-x63et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zjg-x63et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cursor-text" /></template>
