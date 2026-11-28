<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_8qjbb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_8qjbb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:git-merge-check" /></template>
