<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjhyvcc9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jjhyvcc9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hand-peace" /></template>
