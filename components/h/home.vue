<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fudqfvb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fudqfvb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:home" /></template>
