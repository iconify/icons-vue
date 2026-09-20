<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukw-q400c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ukw-q400c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:flip-vertical-16" /></template>
