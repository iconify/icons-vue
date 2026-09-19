<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy6uo1b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yy6uo1b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-up-fill-12" /></template>
