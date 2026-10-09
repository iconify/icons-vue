<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0-d2gbnz.css';
import '../../css/q/q9ku-2ljo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0-d2gbnz"/><path class="q9ku-2ljo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-20" /></template>
