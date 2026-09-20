<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymj5zhe8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ymj5zhe8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow" /></template>
