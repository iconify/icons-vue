<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aki9-bctd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aki9-bctd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:fair" /></template>
