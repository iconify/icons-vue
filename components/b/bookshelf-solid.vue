<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8qdavbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8qdavbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookshelf-solid" /></template>
