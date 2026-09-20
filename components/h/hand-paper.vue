<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvdsl_bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zvdsl_bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-paper" /></template>
