<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3xeyn0am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3xeyn0am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:comment-alt" /></template>
