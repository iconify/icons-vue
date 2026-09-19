<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbzl1cb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="fbzl1cb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:folder" /></template>
