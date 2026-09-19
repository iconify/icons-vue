<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4_d8pb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t4_d8pb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:colx" /></template>
