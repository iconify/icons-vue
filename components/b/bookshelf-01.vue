<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmts5vxbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmts5vxbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookshelf-01" /></template>
