<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4oiey3br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="z4oiey3br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:door-box" /></template>
