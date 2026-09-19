<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-ek5q7td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y-ek5q7td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-control-filled" /></template>
