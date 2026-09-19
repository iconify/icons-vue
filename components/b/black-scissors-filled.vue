<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-9ok0b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j-9ok0b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-scissors-filled" /></template>
