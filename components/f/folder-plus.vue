<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec49kjbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec49kjbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:folder-plus" /></template>
