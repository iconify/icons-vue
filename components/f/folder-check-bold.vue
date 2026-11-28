<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h55a4xb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h55a4xb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:folder-check-bold" /></template>
