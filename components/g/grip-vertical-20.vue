<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9pad14ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c9pad14ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grip-vertical-20" /></template>
