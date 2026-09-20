<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmf2d63wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmf2d63wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:imdb" /></template>
