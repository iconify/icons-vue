<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km0y7xdxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="km0y7xdxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-sitting-wearing-collar" /></template>
