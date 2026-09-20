<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybdunmb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ybdunmb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:drawer" /></template>
