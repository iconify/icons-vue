<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urubo9cau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="urubo9cau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:firefox" /></template>
