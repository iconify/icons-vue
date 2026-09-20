<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju513l7dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ju513l7dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:disconnect" /></template>
