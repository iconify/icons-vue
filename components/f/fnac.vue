<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8mzhkbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g8mzhkbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:fnac" /></template>
