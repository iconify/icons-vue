<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubj89er7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ubj89er7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:btcp" /></template>
