<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymwxane5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ymwxane5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:folder" /></template>
