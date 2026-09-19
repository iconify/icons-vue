<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnn3htbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vnn3htbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:heart" /></template>
