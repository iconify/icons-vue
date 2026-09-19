<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffmwi4b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ffmwi4b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-han" /></template>
