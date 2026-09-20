<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-6_194sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m-6_194sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:angelfish-under-water" /></template>
