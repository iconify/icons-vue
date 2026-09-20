<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4_xc7txx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":104.5,"height":68};
const content = `<path clip-rule="evenodd" class="o4_xc7txx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:babbel" /></template>
