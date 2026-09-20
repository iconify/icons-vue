<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-lgn07dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r-lgn07dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:go-last-16" /></template>
