<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j85tlrbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j85tlrbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:hodl" /></template>
