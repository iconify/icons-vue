<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6d8rs0kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g6d8rs0kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:asciidoc" /></template>
