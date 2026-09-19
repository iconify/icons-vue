<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_1c0ebea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="x_1c0ebea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:broken-heart" /></template>
