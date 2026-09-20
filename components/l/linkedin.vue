<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-zmge8xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q-zmge8xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:linkedin" /></template>
