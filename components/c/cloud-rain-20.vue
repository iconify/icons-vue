<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig5xbqbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ig5xbqbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-rain-20" /></template>
