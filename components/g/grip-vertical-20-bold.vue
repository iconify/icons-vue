<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn493gz6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gn493gz6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grip-vertical-20-bold" /></template>
