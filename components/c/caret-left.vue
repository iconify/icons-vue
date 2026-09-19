<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whxvwgb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="whxvwgb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:caret-left" /></template>
