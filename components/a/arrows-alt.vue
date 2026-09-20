<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/modwem2lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="modwem2lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:arrows-alt" /></template>
