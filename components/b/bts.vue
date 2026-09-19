<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggjpy_jvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ggjpy_jvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bts" /></template>
