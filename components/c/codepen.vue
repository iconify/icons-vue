<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lidk6rnti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lidk6rnti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:codepen" /></template>
