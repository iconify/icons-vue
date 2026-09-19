<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orw-gcrio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="orw-gcrio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:5-square" /></template>
