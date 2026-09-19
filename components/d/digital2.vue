<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbqq-cbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mbqq-cbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital2" /></template>
