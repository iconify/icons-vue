<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afzffgg-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afzffgg-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:bars-3-bottom-right" /></template>
