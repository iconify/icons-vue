<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym09dibfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ym09dibfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cpu-16" /></template>
