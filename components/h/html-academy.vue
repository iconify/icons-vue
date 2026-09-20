<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufsx7q3kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufsx7q3kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:html-academy" /></template>
