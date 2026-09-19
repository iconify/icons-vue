<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhpea7kvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hhpea7kvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cursor-arrow" /></template>
