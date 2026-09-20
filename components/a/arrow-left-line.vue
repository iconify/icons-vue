<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je669obeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je669obeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:arrow-left-line" /></template>
