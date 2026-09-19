<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juxkr3bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="juxkr3bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:annotation" /></template>
