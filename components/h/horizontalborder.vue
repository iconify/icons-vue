<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tor7uzoal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="tor7uzoal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:horizontalborder" /></template>
