<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn9pn5b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn9pn5b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-drop-right" /></template>
