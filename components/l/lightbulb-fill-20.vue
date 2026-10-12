<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxdgsxbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mxdgsxbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lightbulb-fill-20" /></template>
