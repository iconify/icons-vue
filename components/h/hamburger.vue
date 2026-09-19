<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo-95gboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zo-95gboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hamburger" /></template>
