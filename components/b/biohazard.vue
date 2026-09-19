<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu-4c3b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tu-4c3b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:biohazard" /></template>
