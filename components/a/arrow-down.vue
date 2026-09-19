<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzsn6dbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gzsn6dbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:arrow-down" /></template>
