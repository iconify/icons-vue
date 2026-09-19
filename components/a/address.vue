<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9oy42krc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o9oy42krc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:address" /></template>
