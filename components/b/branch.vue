<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y98ul9c4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y98ul9c4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:branch" /></template>
