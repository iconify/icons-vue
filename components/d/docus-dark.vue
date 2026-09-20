<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3zypgb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":32};
const content = `<path clip-rule="evenodd" class="m3zypgb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:docus-dark" /></template>
