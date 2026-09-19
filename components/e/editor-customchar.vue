<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk40dd1ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uk40dd1ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-customchar" /></template>
