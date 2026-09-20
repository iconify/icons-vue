<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4awhmptk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4awhmptk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:1panel" /></template>
