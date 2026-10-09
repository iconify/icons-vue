<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb5l6nbqc.css';
import '../../css/u/u6mkpijxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fb5l6nbqc"/><path class="u6mkpijxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gloves-20" /></template>
