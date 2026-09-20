<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6ud6qgab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v6ud6qgab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffin-with-nine-point-star-outline" /></template>
