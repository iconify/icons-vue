<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3eothw3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="y3eothw3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-dashed-up-left" /></template>
