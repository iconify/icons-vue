<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-2wd-bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c-2wd-bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:debian" /></template>
