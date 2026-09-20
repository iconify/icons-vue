<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn2j1eees.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn2j1eees"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-linear" /></template>
