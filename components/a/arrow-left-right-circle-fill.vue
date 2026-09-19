<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa6k-acml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fa6k-acml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-left-right-circle-fill" /></template>
