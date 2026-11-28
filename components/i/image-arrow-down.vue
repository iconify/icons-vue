<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au7bzabxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au7bzabxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:image-arrow-down" /></template>
