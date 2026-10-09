<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmjswi96d.css';
import '../../css/h/hz6q229uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mmjswi96d"/><path class="hz6q229uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dollar-20-bold" /></template>
