<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpiu6lnbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":730,"height":710};
const content = `<path class="mpiu6lnbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:cloud" /></template>
