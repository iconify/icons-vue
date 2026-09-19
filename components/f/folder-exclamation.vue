<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3lhd6bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d3lhd6bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-exclamation" /></template>
