<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/torkgl_uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="torkgl_uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lightbulb-20-bold" /></template>
